# mof_thermal_bottleneck_si
Supplementary material including the force field parameters used for the thermal conductivity simulations and the input files for the molecular dynamics simulations in [INSERT DOI HERE ONCE PUBLISHED]

The files are provided in the LAMMPS geometry format (.data files) and lammps input files containing the parameters corresponding to the geometry of the systems (.in files)

The force field parameters used in this work are represented in this repository in form of LAMMPS input files that can be used by utilizing the “include” command. The comments after each parameter indicate the type of interaction. E.g. c3_c2h1@ph,h1_c1@ph means the bond of two atoms, the first being a carbon atom, connected to three other atoms, two other carbons and one hydrogen, which is part of a ph (phenyl) group and the other atom is a hydrogen only bound to one other atom, which is carbon. All parameters are given in LAMMPS “real” style units, which means lengths are in Angstroms, energies in kcal/mol and forces in kcal/(mol Angstrom). For further detail about the syntax and meaning of all the commands implore the LAMMPS documentation at https://lammps.sandia.gov/doc/Manual.html. 
