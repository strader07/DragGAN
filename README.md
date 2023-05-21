# DragGAN

:boom: [`Online Demo`](https://df42dcb8c7f4d46917.gradio.live/)

Wild implementation of DragGAN 

[Drag Your GAN: Interactive Point-based Manipulation on the Generative Image Manifold](https://vcai.mpi-inf.mpg.de/projects/DragGAN/)

![demo](assets/demo.png)

**Features**

- [ ] Support movable region. 
- [ ] Mutliple handle points.
- [x] Automatically download stylegan2 checkpoint.
- [x] Gradio Demo.
- [x] Workable version.


**Demo video**

https://github.com/Zeqiang-Lai/DragGAN/assets/26198430/cea01f21-3021-40fc-8221-58db0bd7b057




## Usage

Ensure you have [PyTorch](https://pytorch.org/get-started/locally/), [Gradio](https://gradio.app/quickstart/), and [tqdm](https://github.com/tqdm/tqdm) installed.

```bash
pip install -r requirements.txt
```

Lanuch the Gradio demo

```
python gradio_app.py
```

> If you have any issuse for downloading the checkpoint, you could mannuly download it from [here](https://huggingface.co/aaronb/StyleGAN2/tree/main) and put it into the folder `checkpoints`.

## Acknowledgement

[Official DragGAN](https://github.com/XingangPan/DragGAN) &ensp; [StyleGAN2](https://github.com/NVlabs/stylegan2)  &ensp; [StyleGAN2-pytorch](https://github.com/rosinality/stylegan2-pytorch)

## Citation

```bibtex
@inproceedings{pan2023draggan,
    title={Drag Your GAN: Interactive Point-based Manipulation on the Generative Image Manifold}, 
    author={Pan, Xingang and Tewari, Ayush, and Leimk{\"u}hler, Thomas and Liu, Lingjie and Meka, Abhimitra and Theobalt, Christian},
    booktitle = {ACM SIGGRAPH 2023 Conference Proceedings},
    year={2023}
}
```