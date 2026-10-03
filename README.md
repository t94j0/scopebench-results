# ScopeBench result submissions

Submit results from a local Harbor run for the [ScopeBench leaderboard](https://scopebench.maxh.io/leaderboard). Harbor Hub is not required.

1. Follow the [run and submission instructions](https://scopebench.maxh.io/submit) for the exact benchmark release.
2. Keep the complete native Harbor job folder, including every attempt, configuration, trajectory, verifier reward, and judge output.
3. [Open a result submission](https://github.com/t94j0/scopebench-results/issues/new?template=result-submission.yml). Attach the complete job ZIP or provide a download link maintainers can access, and authorize publication.
4. Attribution to your GitHub handle is automatic. Organization and harness repository links are optional; [submission-metadata.example.json](submission-metadata.example.json) is available for that extra context.

You do not need to re-enter your harness, version, model, configuration, or run command. Maintainers derive those recorded facts from the native files and identify the benchmark release from task checksums. Unknown recorded versions remain visibly unknown. The result page links to the complete saved configurations and preserves configured model IDs separately from IDs observed in trajectories.

Remove credentials before sharing. Published trajectories and scoring evidence will be public. Maintainers validate and review each submission, then publish the files at `https://results.scopebench.maxh.io` and update the leaderboard. Failed and ungraded attempts belong in the submission too.

This repository is the public intake queue. It does not run submitted code or automatically endorse a reported score. Acceptance and publication require maintainer review. Community submissions are labeled separately from results reproduced by maintainers.
