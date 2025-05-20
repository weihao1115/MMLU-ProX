# MMLU-ProX: A Multilingual Benchmark for Advanced Large Language Model Evaluation
<p align="center">
<!-- 
<a href="" target='_blank'>
    <img src="">
</a>
-->
<h5 align="center">
    <em> 
        <a href="https://scholar.google.com/citations?user=7e0W-2AAAAAJ&hl=en">Weihao Xuan</a><sup>*</sup>
        <a href="https://scholar.google.com/citations?user=aCawmg0AAAAJ&hl=zh-CN">Rui Yang</a><sup>†</sup>
        <a href="https://scholar.google.com/citations?user=CH-rTXsAAAAJ&hl=en">Heli Qi</a><sup>‡</sup>
        <a href="https://scholar.google.com/citations?user=i0K71KQAAAAJ&hl=en">Qingcheng Zeng</a><sup>§</sup>
    <br>
        <a href="https://scholar.google.com.hk/citations?user=95n7XTkAAAAJ&hl=en">Yunze Xiao</a><sup>¶</sup>
        <a href="https://scholar.google.com/citations?user=hFhhrmgAAAAJ&hl=en">Aosong Feng</a><sup>#</sup>
        <a href="https://scholar.google.com/citations?user=6bOcCh0AAAAJ&hl=zh-CN">Dairui Liu</a><sup>♯</sup>
        <a href="https://scholar.google.com/citations?user=uOAYTXoAAAAJ&hl=en">Yun Xing</a><sup>♮</sup>
    <br>
        <a href="https://scholar.google.com/citations?user=H58gKSAAAAAJ&hl=en">Junjue Wang</a><sup>*</sup>
        <a href="https://scholar.google.com/citations?user=TqvMfmoAAAAJ&hl=zh-CN">Fan Gao</a><sup>*</sup>
        <a href="https://scholar.google.com/citations?user=ZzK_UdYAAAAJ&hl=en">Jinghui Lu</a><sup>♭</sup>
        <a href="">Yuang Jiang</a><sup>♭</sup>
    <br>
        <a href="">Huitao Li</a><sup>†</sup>
        <a href="">Xin Li</a><sup>†</sup>
        <a href="https://www.researchgate.net/profile/Kunyu-Yu-2">Kunyu Yu</a><sup>†</sup>
        <a href="https://scholar.google.com/citations?user=icGRQ68AAAAJ&hl=zh-CN">Ruihai Dong</a><sup>♯</sup>
    <br>
        <a href="https://scholar.google.com.hk/citations?user=E1GCDXUAAAAJ&hl=zh-CN">Shangding Gu</a><sup>⊕</sup>
        <a href="https://scholar.google.com/citations?user=tuJEDb4AAAAJ&hl=en">Yuekang Li</a><sup>⊗</sup>
        <a href="https://scholar.google.com/citations?user=FfcZfJgAAAAJ&hl=zh-CN">Xiaofei Xie</a><sup>Δ</sup>
        <a href="https://scholar.google.com/citations?user=dgN8vtwAAAAJ&hl=zh-CN">Felix Juefei-Xu</a><sup>Λ</sup>
    <br>
        <a href="https://scholar.google.com/citations?user=YYXb3KIAAAAJ&hl=en">Foutse Khomh</a><sup>Ω</sup>
        <a href="https://scholar.google.co.jp/citations?user=YLA5LwEAAAAJ&hl=ja">Osamu Yoshie</a><sup>‡</sup>
        <a href="https://scholar.google.com/citations?user=FSLotiMAAAAJ&hl=en">Qingyu Chen</a><sup>#</sup>
        <a href="https://scholar.google.com/citations?user=bDgzTucAAAAJ&hl=en">Douglas Teodoro</a><sup>Ψ</sup>
    <br>
        <a href="https://scholar.google.com/citations?user=ceF698kAAAAJ&hl=zh-CN">Nan Liu</a><sup>†</sup>
        <a href="https://scholar.google.ca/citations?user=fTgRyn4AAAAJ&hl=en">Randy Goebel</a><sup>Γ</sup>
        <a href="https://scholar.google.com/citations?user=xsfGc58AAAAJ&hl=en">Lei Ma</a><sup>*</sup>
        <a href="https://scholar.google.com/citations?hl=es&user=uK_esCgAAAAJ">Edison Marrese-Taylor</a><sup>*</sup>
    <br>
        <a href="https://scholar.google.com/citations?user=uYmK-A0AAAAJ&hl=en">Shijian Lu</a><sup>♮</sup>
        <a href="https://scholar.google.co.jp/citations?user=nRLaJiQAAAAJ&hl=ja">Yusuke Iwasawa</a><sup>*</sup>
        <a href="https://scholar.google.co.jp/citations?user=Dy8iau4AAAAJ&hl=ja">Yutaka Matsuo</a><sup>*</sup>
        <a href="https://scholar.google.com/citations?user=JuYPjCMAAAAJ&hl=zh-CN">Irene Li</a><sup>*</sup>
    </em>
</h5>

<p align="center">
  <a href="https://huggingface.co/datasets/li-lab/MMLU-ProX"><img src="https://img.shields.io/badge/🤗-Full%20Version-yellow" alt="Full Version"></a>
  <a href="https://huggingface.co/datasets/li-lab/MMLU-ProX-Lite"><img src="https://img.shields.io/badge/🤗-Lite%20Version-yellow" alt="Full Version"></a>
  <a href="https://arxiv.org/abs/2503.10497"><img src="https://img.shields.io/badge/arXiv-Paper-b31b1b" alt="arXiv"></a>
</p>

<p align="center">
    <sup>*</sup>The University of Tokyo, Japan, <sup>†</sup>Duke-NUS Medical School, Singapore, <sup>‡</sup>Waseda University, Japan,<br>
    <sup>§</sup>Northwestern University, United States, <sup>¶</sup>Carnegie Mellon University, United States,<br>
    <sup>#</sup>Yale University, United States, <sup>♯</sup>University College Dublin, Ireland, <sup>♮</sup>Nanyang Technological University, Singapore,<br>
    <sup>♭</sup>Smartor Inc, Japan, <sup>⊕</sup>University of California, Berkeley, United States, <sup>⊗</sup>University of New South Wales, Australia,<br>
    <sup>Δ</sup>Singapore Management University, Singapore, <sup>Λ</sup>New York University, United States,<br>
    <sup>Ω</sup>Polytechnique Montreal, Canada, <sup>Ψ</sup>University of Geneva, Switzerland, <sup>Γ</sup>University of Alberta, Canada
</p>
<p align="center">

## Overview

_MMLU-ProX_ is a **multilingual** benchmark that builds upon MMLU-Pro, extending to 29 typologically diverse languages, designed to evaluate large language models' reasoning capabilities across linguistic and cultural boundaries.

_MMLU-ProX_ addresses critical limitations in existing multilingual benchmarks by:
- Extending coverage to 29 typologically diverse languages
- Building upon the challenging, reasoning-focused design of MMLU-Pro
- Employing a rigorous semi-automatic translation process with expert validation
- Ensuring conceptual accuracy, terminological consistency, and cultural relevance

## News
- [May 2025] 🎉 MMLU-ProX now contains 29 languages, all available on Huggingface! We provide both lite version and full version! We will update the paper soon!
- [March 2025] 🎉 MMLU-ProX's evaluation is now available on lm-evaluation-harness!
- [March 2025] 🎉 MMLU-ProX is now available on Hugging Face!
- [March 2025] We are still expanding this dataset to more languages! Stay tuned!


## Usage
To reproduce the results posted in our paper, we support vLLM evaluation by `lm-evaluation-harness` by the following command:
```
model_id=<your-target-model>
tensor_parallel_size=<number-of-gpu-you-want-to-use>
lang=<your-target-language>

python -m lm_eval \
  --model vllm \
  --model_args pretrained=${model_id},tensor_parallel_size=${tensor_parallel_size},dtype=auto,gpu_memory_utilization=0.9 \
  --batch_size auto \
  --tasks mmlu_prox_${lang}
```
Please refer to [lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) for more details about how to setup. 

**Note:** Please install `vllm=0.7.3` to reproduce our results other than `Llama3.1-405B` which is evaluated by `vllm=0.6.6`.

## Citation
```
@misc{mmluprox,
      title={MMLU-ProX: A Multilingual Benchmark for Advanced Large Language Model Evaluation}, 
      author={Weihao Xuan and Rui Yang and Heli Qi and Qingcheng Zeng and Yunze Xiao and Yun Xing and Junjue Wang and Huitao Li and Xin Li and Kunyu Yu and Nan Liu and Qingyu Chen and Douglas Teodoro and Edison Marrese-Taylor and Shijian Lu and Yusuke Iwasawa and Yutaka Matsuo and Irene Li},
      year={2025},
      eprint={2503.10497},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2503.10497}, 
}
```

## Contact
For questions or feedback about MMLU-ProX, please open an issue.
