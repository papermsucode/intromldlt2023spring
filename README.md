# Introduction to Machine and Deep Learning Theory

## Content
* [News](#news)
* [Short info](#info)
* [Time and place](#ww)
* [Communication with teachers](#feedback)
* [Task results](#marks)
* [Course program](#program)
* [Projects proposals](#project)
* [Bibliography](#lit)
* [Useful links](#links)

## <a name="news" /> News
* The first lecture will take place on Wednesday 8, February, at 16:45 (online) 

## <a name="info" /> Short info 
In the spring semester of 2023 at the Faculty of Mechanics and Mathematics of Lomonosov Moscow State University a new special [course](https://scs.math.msu.ru/node/3164) of the student's choice, dedicated to the theory of machine learning and deep learning, is to be provided.

The course will be taught on the basis of the Department of [Mathematical Theory of Intelligent Systems](http://intsys.msu.ru/en/) under the guidance of Ph.D., Senior Researcher [Mazurenko I.L.](http://intsys.msu.ru/staff/mazurenko/) The course will be taught by Ph.D. [Petiushko A.A.](https://petiushko.info)

## <a name="ww" /> Time and place 
Classes are to be taught on Wednesdays at 16:45, online. 

## <a name="feedback" /> Communication with teachers
* [Telegram-channel](https://t.me/+OX_Ie45QTghjZmJi), where all important news will appear
* Feedback - by email papermsucode@gmail.com
* Well, you can always write in [issues](https://github.com/papermsucode/intromldlt2023spring/issues) :)

## <a name="marks" /> Task results
* [Summary table with results will be shared soon]()

## <a name="program" /> Course program
| Number        | Date          | Lecture                                            | Video            |
| ------------- | ------------- | -------------                                      | -------------    |        
| 01            | 08.02.2023    | [Empirical Risk and its Approximation. Loss Function. (Stochastic) Gradient Descent. MLE and MAP. Kullback-Leibler divergence and Cross Entropy](/lectures/MM_lecture01-ER_Loss.pdf) |  [lecture01](https://www.youtube.com/watch?v=vBgo_T7V5hE)   |
| 02            | 15.02.2023    | [FaceID: Evolution of Loss Function. Representation Learning. SoftMax-, contrastive- and angular-based losses](/lectures/MM_lecture02-FaceID_Loss.pdf) |  [lecture02](https://www.youtube.com/watch?v=4dwmNbMqcwg)  |
| 03            | 22.02.2023    | [Discriminate vs Generative models. Generative Adversarial Networks. Deep Convolutional GAN. Wasserstein GAN. Gradient-Penalty WGAN. Conditional GAN.](/lectures/MM_lecture03-GAN.pdf) |  [lecture03](https://www.youtube.com/watch?v=qb-4TQIUrzY)  |
| 04            | 01.03.2023    | [Bayesian Inference, Bayesian Neural Network, Variational Inference, Autoencoder, Variational Autoencoder, Conditional Variational Autoencoder](/lectures/MM_lecture04-VI_AE_VAE_CVAE.pdf) |  [lecture04](https://www.youtube.com/watch?v=Wf-Hm0SzP5s)  |
| 05            | 15.03.2023    | [Recap of Markov Chains. Markov Chain Monte Carlo. Gibbs sampler. Metropolis-Hastings sampler. Langevin dynamics and Metropolis-Adjusted Langevin. Stochastic Gradient Langevin Dynamics](/lectures/MM_lecture05-MCMC.pdf) |  [lecture05](https://www.youtube.com/watch?v=FzXEP_JHTgw)  |
| 06            | 22.03.2023    | [Recap of Variational Autoencoder. Markovian Hierarchical VAE. Diffusion models: Variational Diffusion Models, Diffusion Denoising Probabilistic Models, Diffusion Denoising Implicit Models, Classifier and classifier-free guidance, 3 interpretations](/lectures/MM_lecture06-Diffusion.pdf) |  [lecture06](https://www.youtube.com/watch?v=zeYZfeuvxDk)  |
| 07            | 29.03.2023    | [Adversarial Robustness I: Great Success of CNNs, Robustness Phenomenon, Taxonomy of Adversarial Attacks, l_p norms, Digital Domain, Fast Gradient Sign Method and its variants, Universal Attacks, Top-k Attacks, l_0 attacks](/lectures/MM_lecture07-AdvRob_I_Digital.pdf) |  [lecture07](https://www.youtube.com/watch?v=iWjErgoxJuo)  |

## <a name="project" /> Projects proposals
1. Investigate Neural Collapse on different datasets (MNIST, Omniglot, LFW, ...)
2. Make a comparison study of angular-based losses vs metric-based ones on different datasets (MNIST, Omniglot, LFW, ...)
3. Think of evaluation metric for GAN solution (aside from [Inception Score](https://en.wikipedia.org/wiki/Inception_score) / [Frechet Inception Distance](https://en.wikipedia.org/wiki/Fréchet_inception_distance)) and make a coparison study of this metric for different GAN solution: vanilla GAN, WGAN, WGAN-GP
4. Implement and analyze the BNN recognition results using different priors for weights (Uniform, Gaussian, Laplace) on different datasets (MNIST, Omniglot, LFW, ...)
    1. Do it with Variational Inference
    2. Do it with MCMC
5. Explore the Diffusion generation quality vs number of steps on different datasets (MNIST, Omniglot, LFW, ...)
    1. Do it with unconditional generation
    2. Do it with classifier(-free) guidance
    3. Explore different strategies of $\alpha$ ($\beta$) decrease schedule

## <a name="lit" /> Bibliography
1. [Machine Learning Lecture Course](http://www.machinelearning.ru/wiki/index.php?title=Машинное_обучение_%28курс_лекций%2C_К.В.Воронцов%29) on http://www.machinelearning.ru from Vorontsov K.V.
2. Hastie, T. and Tibshirani, R. and Friedman, J. [The Elements of Statistical Learning](https://web.stanford.edu/~hastie/ElemStatLearn/printings/ESLII_print12.pdf), 2nd edition, Springer, 2009.
3. Bishop, C.M. [Pattern Recognition and Machine Learning](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf), Springer, 2006.
4. Ian Goodfellow, Yoshua Bengio, Aaron Courville, and Yoshua Bengio. Deep learning. Vol. 1. Cambridge: MIT press, 2016.
5. Matus Telgarsky, Deep learning theory lecture [notes](https://mjt.cs.illinois.edu/dlt/index.pdf), 2021
6. Sanjeev Arora et al., Theory of Deep learning book [draft](https://www.dropbox.com/s/smkp4vasbiszhw4/DLbook.pdf?dl=0), 2020

## <a name="links" /> Useful links 
### Introduction to machine learning
* Homemade Machine Learning: [github repo](https://github.com/trekhleb/homemade-machine-learning)
* Machine learning: [Course](https://www.coursera.org/learn/machine-learning) by Andrew Ng on the site https://www.coursera.org

### Theoretic Courses
* Foundations of Deep Learning: [Course](https://uclaml.github.io/CS269-Spring2021/) at UCLA
* Deep learning theory: [Course](https://mjt.cs.illinois.edu/dlt/) at UIUC
* Theoretical Deep Learning: [Course](https://www.cs.princeton.edu/courses/archive/fall19/cos597B/) at Princeton
