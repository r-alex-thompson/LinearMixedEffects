# LinearMixedEffects

Welcome to the Linear Mixed Effects Models workshop. This is just a simple ReadMe document that outlines some of the things we'll discuss today, and what the files are. I designed this workshop to be a simplification of some of the things I've learned in classes, through books, and via osmosis. Basically, the idea is to hopefully shed light on what mixed effects models are, when to use them, and how they work. We'll cover 3 main types of mixed models: 

1. Linear Mixed Effects Models 
    This is the most common type of mixed effects models, and often what people refer to when they say mixed effects. This is just like linear model but it allows one to specify something called a random effect. Essentially, if one has repeated measures or some type of autocorrelation (i.e., treatment) in their data, the LME model is useful for deriving accurate statistics against which one can test.
    
2. Generalized Linear Mixed Effects Models
    This is the second most common type of mixed model. A usual assumption with linear models is that our dependent (y) variable is normally distributed around our slope. In other words, it works by fitting a line through the center of a normal distribution of data. Yet, count or presence absence data doesn't follow a normal distribution but is often poisson or negative binomially distributed. Moreover, issues with heteroscedasticity (i.e., sampling intensity can cause this) make a normal LME infeasible. One can use a GLM to specify the poisson or NB model!
    
3. General Estimating Equations
    Probably the least common of the 3 types of models we'll discuss. GEEs work like an LME or GLM by accounting for a random effect. Yet, instead of conditioning on those random effects like LME or GLM, GEEs marginalize or integrate out that random variance. This can often be useful if one is more interested in the overall population response and not group-level responses.
    
