# NInfer exact-source recovery builder

Temporary public hosted builder created for J25/G10 after the local Docker image was garbage-collected during VHDX cleanup.

It checks out public source commit `c55dcf359730c0d2e6c310f670966c25cf67870b`, builds the two `sm_89` binaries and dashboard into a CUDA 13.2 slim image, verifies that no model weight is present, and publishes a split Docker archive as a GitHub release.

No model weights, credentials, private project files, or user data are included.
