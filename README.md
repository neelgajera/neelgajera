# Hi, I'm Neel Gajera

**Senior Computer Vision Engineer**, working on 3D reconstruction, neural rendering and generative imaging. New Delhi, India.

I have 5+ years of taking vision research into production. At Spyne I led a team that turned a phone walk-around video
into a photorealistic 3D car (Gaussian/Beta splatting, SfM, Difix3D+, 3D segmentation, a web viewer), and shipped Vini,
a production voice agent. I'm now an ML Engineer II at Aftershoot, working on aesthetic auto-cropping and white-balance models.

**Open to computer vision and 3D roles, in India or remote:** [neelgajera09@gmail.com](mailto:neelgajera09@gmail.com) ·
[LinkedIn](https://linkedin.com/in/neel-gajera-09152313a)

## Live demo

[![3D cars reconstructed from phone videos, in a studio with shadows and reflections](https://raw.githubusercontent.com/neelgajera/beta-splatting-showcase/main/docs/studio.jpg)](https://neelgajera.github.io/beta-splatting-showcase/studio.html)

Three cars reconstructed from 70-second phone videos, running in your browser:
[**gallery and viewer**](https://neelgajera.github.io/beta-splatting-showcase/) ·
[**studio**](https://neelgajera.github.io/beta-splatting-showcase/studio.html) (PlayCanvas, cast shadows, reflections, HDRI lighting)

## Projects: a phone video to a 3D car

| Repo | What it does |
|---|---|
| [video-to-splat](https://github.com/neelgajera/video-to-splat) | Phone video to photorealistic 3D: motion-aware frame selection, COLMAP or VGGT poses, licence plates replaced in 3D, Deformable Beta Splatting trained on a 6 GB GPU |
| [spin-stabilizer](https://github.com/neelgajera/spin-stabilizer) | A hand-held 360° walk-around becomes a level, evenly spaced turntable spin, using SfM or VGGT camera poses |
| [splat-segment](https://github.com/neelgajera/splat-segment) | Cuts the car out of the splat with multi-view mask voting, and clips it cleanly at render time with a CUDA implementation of RaRa Clipper ([arXiv 2506.20202](https://arxiv.org/abs/2506.20202)) |
| [difix-turbo](https://github.com/neelgajera/difix-turbo) | A from-scratch Difix3D+: single-step diffusion (SD-Turbo + LoRA) that removes artifacts from novel-view renders |
| [beta-splatting-showcase](https://github.com/neelgajera/beta-splatting-showcase) | The web gallery and studio above: a Beta-splatting renderer in three.js, a Beta→3DGS converter, proxy-mesh shadows in PlayCanvas |

<p>
  <img src="https://raw.githubusercontent.com/neelgajera/spin-stabilizer/main/docs/chevy_before_after.gif" width="49%" alt="Hand-held walk-around (left) and the stabilized turntable spin (right)">
  <img src="https://raw.githubusercontent.com/neelgajera/splat-segment/main/docs/turntable.gif" width="49%" alt="Car cut out of its splat scene">
</p>

## Toolbox

**3D vision:** Gaussian and Beta splatting, NeRF, SfM/MVS (COLMAP, HLoc, SuperPoint/SuperGlue), VGGT, 3D segmentation  
**Generative:** diffusion (SDXL, SD-Turbo, Difix3D+), inpainting, GANs (pix2pix, CycleGAN, CUT)  
**Deployment:** PyTorch, CUDA, TensorRT, ONNX, Triton, quantization, NCNN/TFLite on mobile  
**Web:** three.js, PlayCanvas, WebGL
