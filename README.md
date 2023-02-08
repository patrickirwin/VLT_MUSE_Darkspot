# VLT_MUSE_Darkspot
Repository of data files associated with VLT/MUSE Darkspot Paper

This repository contains files used to determine the spectra of the NDS-2018 and DBS-2019 features in Neptune's Atmosphere from observations made in 2019 with the MUSE instrument at the Very Large Telescope (VLT) in Chile and reported in Nature Astronomy.

The data files are as follows.

For Figure 1:
1) difference_spectra_edit.txt - lists the difference spectra of NDS-2018, DBS-2019 and SBS features. The units are I/F.

For Figure 2:

1) profile_nds.txt - atmospheric T/P/vmr and cloud profiles used for Minnaert-fit to 10-20N latitude band. The units of cloud amount are particles/gram, but the profiles have been normalised such that total integrated cloud amount is the integrated opacity of the cloud at 800 nm.
2) amounts_nds.txt - the actual path layers and amounts used in the radiative transfer calculation.
3) data_summary_nds.txt - a summary of the refractive index data of the three aerosol types and the cloud opacities for the reference Minnaert fit to the 10-20N latitude band and also to the NDS-2018 spectrum and the expected spectrum at the NDS-2018 location.
4) scat_summary_NDS.txt - summary of the particle scattering properties. This also appears in Supplementary tables 2 - 6.
5) compare_spectra_nds.txt - the spectra fitted to in the NDS-2018 region and the expected background spectrum.

For Figure 3:

1) profile_dbs.txt - atmospheric T/P/vmr and cloud profiles used for Minnaert-fit to 5-15N latitude band. The units of cloud amount are particles/gram, but the profiles have been normalised such that total integrated cloud amount is the integrated opacity of the cloud at 800 nm.
2) amounts_dbs.txt - the actual path layers and amounts used in the radiative transfer calculation.
3) data_summary_dbs.txt - a summary of the refractive index data of the three aerosol types and the cloud opacities for the reference Minnaert fit to the 10-20N latitude band and also to the DBS-2019 spectrum and the expected spectrum at the DBS-2019 location.
4) scat_summary_DBS.txt - summary of the particle scattering properties. This also appears in Supplementary tables 2 - 6.
5) compare_spectra_dbs.txt - the spectra fitted to in the DBS-2019 region and the expected background spectrum.

