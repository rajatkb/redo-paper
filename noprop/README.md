# NoProp : Training Neural Networks without Full Back-propagation or Full Forward-propagation

paper : [link](https://arxiv.org/abs/2503.24322)

### Why do I care ?
- Because I want single shot step for N layers neural network. No more running backward after every forward pass. 😎
- Even though we don't do analytical differentitaion and rely on auto-diff which is partial chain differentiation on steroids, IMO the approach still always leads noisy updates. Which lead to creation of every flavour of Optimizer to keep the noisy updates under check. If I look at work in statistics and sampling strategies it looks like there is some decent ideas that although not directly transferable but can still be utilised for better sampling of parameter distribution. 😐
- Paper has enough novel factor and reference worth writing a notebook on 😂


### Paper Summary & Notes
