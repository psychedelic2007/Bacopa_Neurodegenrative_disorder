# Bacopa_Neurodegenrative_disorder

## gmx covar -f md_0_10_center_drug.xtc -s md_0_10.tpr -n index.ndx -b 140000 -e 150000 -v eigenvec.trr

## gmx anaeig -v eigenvec.trr -f md_0_10_center_drug.xtc -eig eigenval.xvg -s md_0_10.tpr -n index.ndx -first 1 -last 4 -2d pc1_pc4.xvg 
