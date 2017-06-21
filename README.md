
Overview of amyloid PET for AD data.

Build the document with RStudio and `ANTsR`.

this repo uses  https://git-lfs.github.com/

you may need to install git lfs then use

git lfs fetch --all

to reproduce the examples here.

also note that - depending on the amyloid data - one may 

want another registration step for large-scale applications.

e.g. build an amyloid template and use it to roughly extract 

the brain from the amyloid image.   then

one can rigidly register to the t1 brain more accurately.

