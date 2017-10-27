# Spatial ecology cheatsheet

This is a rather random assortment of references on issues of geometry, fractals, aggregation and scaling in ecology. Mostly stuff that I learned from my teachers during my PhD studies and during my first postdoctoral years.

## General treatments

- [Storch et al. 2007](http://ebooks.cambridge.org/ebook.jsf?bid=CBO9780511814938) put together a multiauthor book which is highly relevant on the issues of scaling, biodiversity, fractals, species-area relationships and geometry.
- [Storch et al. 2008](http://www.cts.cuni.cz/~storch/publications/Storch_et_al_2008.pdf)'s Figure 1 gives a good overview of how different spatial patterns are connected.
- [Storch 2016](http://www.cts.cuni.cz/~storch/publications/Storch_2016_JVS_Nested_SAR.pdf) summarizes the general theory of nested species-area relationships.

## Fractals in ecology

- [Brown et al. 2002](http://www.fractal.org/Bewustzijns-Besturings-Model/Fractal-Nature.pdf) on fractal nature of nature.
- [Halley et al. 2004](http://www.uvm.edu/~pdodds/files/papers/others/2004/halley2004a.pdf) provide, to my knowledge, the most useful and authoritative practical intro to fractals in ecology.
- [Lennon et al. 2002](http://personal.victoria.ac.nz/stephen_hartley/pdfs/Lennon%20et%20al%2002%20OIKOS%20fractal%20SAR.PDF) makes the point that fractal species distributions do not produce power-law species area relationship. 

## Why should species distributions (and the world) be fractal?

- [Peckham et al. 2010](http://onlinelibrary.wiley.com/wol1/doi/10.1029/94WR03155/abstract) contemplates fractal in river networks.
- [Morse et al. 1985](http://www.nature.com/nature/journal/v314/n6013/pdf/314731a0.pdf) on fractal dimensions of vegetation.

## Cross-scale aggregation of single-species distributions, occupancy-area relationships

- [Kunin 1998](http://science.sciencemag.org/content/281/5382/1513.full-text.pdf+html) has started it all.
- [Azaele et al. 2012](https://www.researchgate.net/publication/225077957_Downscaling_species_occupancy_from_coarse_spatial_scales) provide the best introduction to and evaluation of single-species occupancy downscaling.
- [Hartley et al. 2004](http://rspb.royalsocietypublishing.org/content/271/1534/81) describe how species aggregation at different scales reflects different processes. The paper title is quite telling: "Coherence and discontinuity in the scaling of specie's distribution patterns".
- [Barwell et al. 2014](http://onlinelibrary.wiley.com/doi/10.1111/ddi.12203/full) -- more on downscaling.

## Can static scaling of species distributions predict range dynamics and biodiversity change?

- [Wilson et al. 2004](http://www.nature.com/nature/journal/v432/n7015/full/nature03031.html) show, in a really original and fun paper, how scaling of static species distributions can predict temporal range dynamics, and ultimately, biodiversity change.

## Scaling of beta diversity, distance decays, SAR

- [Mokany et al. 2013](http://onlinelibrary.wiley.com/doi/10.1111/jbi.12175/full) did simulation study exploring scaline of paiwise beta diversity with area.
- [Mokany et al. 2011](http://onlinelibrary.wiley.com/doi/10.1111/j.1461-0248.2011.01675.x/full) made a crazy algorithm that can combine alpha and beta diversity to predict spatial patterns of both richness and composition.
- [Keil et al. 2012](http://onlinelibrary.wiley.com/doi/10.1111/j.1365-2699.2012.02701.x/abstract) explore spatial scaling of distance decay of similarity.
- [Sizling & Storch 2004](http://www.cts.cuni.cz/~storch/publications/Sizling%20&%20Storch%202004.pdf) write on species-area relationships, fractals, beta diversity and self-similarity.
- [Azaele et al. 2014](http://onlinelibrary.wiley.com/doi/10.1111/2041-210X.12319/abstract) predict patterns of biodiversity across spatial scales using pair correlation function.
- [Lennon et al. 2001](http://onlinelibrary.wiley.com/doi/10.1046/j.0021-8790.2001.00563.x/pdf) show how beta diversity and species-area relationships vary geographically over the UK.
- [Storch et al. 2012](http://www.cts.cuni.cz/~storch/publications/Storch_et_al_2012_Nature_Universal_SAR_and_EAR.pdf) shows universal SAR accross multiple taxa and globally.

## Patterns of aggregation

- Dylan has pointed me out to [Condit et al. 2000](http://faculty.jsd.claremont.edu/dmcfarlane/bio176mcfarlane/pdf%20papers/Condit%20et%20al%202000.pdf) who found that most BCI trees follow spatial distribution that deviates from random.
- [Storch et al. 2008](http://www.cts.cuni.cz/~storch/publications/Storch_et_al_2008.pdf) write on cross-scale aggregation of species, self similarity and present the idea of generalized fractals. Their Fig. 1 also give useful review of the links between the patterns.
 
## Species-abundance distributions

- [Sizling et al. 2009](http://www.cts.cuni.cz/~storch/publications/Sizling_et_al_2009_PNAS.pdf) write on aggregation of species-abundance distributions.

## Spatial scaling of biotic interactions

- [Araujo & Rozenfeld 2014](http://onlinelibrary.wiley.com/doi/10.1111/j.1600-0587.2013.00643.x/full) write on sptail scaling of biotic interactions.
- [Seguardo et al. 2012](https://www.researchgate.net/publication/232273519_Patterns_of_coexistence_of_two_species_of_freshwater_turtles_are_affected_by_spatial_scale) write on scale-dependency of coexistence of two species of freshwater turtles.
 
## Upscaling local samples to estimate large-scale richness

- [Mokany et al. 2011](http://onlinelibrary.wiley.com/doi/10.1111/j.1461-0248.2011.01675.x/full). Potentially, their algorithm can be used to upscale species richness.
- [Zillio & He 2010](https://sites.ualberta.ca/~fhe/He-publications/Zillio_He.Oikos2010.pdf) present a Bayesian method to upscale SADs.
- [Shen & He 2008](https://sites.ualberta.ca/~fhe/He-publications/Shen_He.Ecology08.pdf) use zero-truncated binomial distribution to upscale.
- [Rominger & Merrow 2016](http://www.onlinelibrary.wiley.com/doi/10.1111/2041-210X.12625/abstract) introduce R package MeteR (package for testing predictions of Maximum Entropy Theory of Ecology), which can be used to upscale richness. 

## Statistical downscaling in ecology and macroecology

- [McInerny & Purves 2011](http://onlinelibrary.wiley.com/doi/10.1111/j.2041-210X.2010.00077.x/abstract) show how to estimate fine-grain niche from coarse-grain environmental data and point species detections.
- [Keil et al. 2012](http://onlinelibrary.wiley.com/doi/10.1111/j.2041-210x.2012.00264.x/full) show how to do the opposite, i.e. how to estimate fine-grain species distribution from coarse-grain occurrences and fine-grain environment.
- [Keil et al. 2014](http://onlinelibrary.wiley.com/doi/10.1890/13-0805.1/full) show how to downscale spatial patterns of species richness.

## Spatial properties of range maps vs. point detections
- [Merrow et al. 2016](http://onlinelibrary.wiley.com/doi/10.1111/geb.12539/abstract) show some elegant and simple tricks for how to combine point data with range maps to map species distributions.
- [Hurlbert & Jetz 2007](http://www.pnas.org/content/104/33/13384.full) write on scale-dependence of range maps and on the "minimum reliable resolution" of ~ 100 x 100 km^2.
- [Keil et al. 2014](http://onlinelibrary.wiley.com/doi/10.1111/ddi.12199/abstract) further dissects the reliability and scale-dependence of range maps and point records. A lot of the work is in the appendix.




