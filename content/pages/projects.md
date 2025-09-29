---
content_type: page
description: This section provides information on the final project for the course.
  The final project includes molecular studies of three different systems, including
  (i) a nanowire, (ii) fracture of a single crystal of silicon and (iii) deformation
  and unfolding of a protein. All three examples serve the purpose of becoming more
  acquainted with MD, including setting up problems, analysis methods and interpretation
  of results.
hide_download: true
hide_download_original: null
learning_resource_types:
- Projects
ocw_type: CourseSection
title: Projects
uid: 90f60c06-d578-ff04-ac25-c2799d5bf7d9
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

Final Project Introduction ({{% resource_link 8d7ae187-a7da-c9be-7da6-1c1273918154 "PDF" %}})

Problem A ({{% resource_link b42beef9-3460-c6e8-2472-43c1229558e5 "PDF" %}})

Problem B ({{% resource_link 344ca361-ed85-307e-84ad-8f9887b77555 "PDF" %}})

Problem C ({{% resource_link 1f85de43-26a1-e772-9661-13fed218ac79 "PDF" %}})

### For Problem C

Initial structure ({{% resource_link c5afb4f1-770c-b9a2-4b1e-56921736daf6 "PDB" %}}) This is the initial structure (obtained from Protein Data Bank; after processing).  
Structure file ({{% resource_link 78777e54-4d70-b132-4024-f830da16a607 "PSF" %}})  
Initial fix.pdb file (specify fixed atoms) ({{% resource_link 8c650734-8e0a-9d76-7759-171147ab00f9 "PBD" %}})  
Initial smd.pdb file (specify atoms that are being pulled) ({{% resource_link a5f590e4-585a-046c-a393-abdf67f8c4a5 "PDB" %}})

### Simulation Results

CMDF - Log file run mode I (short) ({{% resource_link 4d999063-a464-1d75-afde-5a941b448dcd "XYZ" %}}) This .xyz file shows a sequence of crack propagation (1,000 steps, as in the example script given above). Frequency of snapshot writing, time step etc. is the same in all examples, and equal to the example script. You may directly load this file into VMD and carry out the analysis.

CMDF - Log file run mode II ({{% resource_link 37e81cc2-d4da-7ca2-1086-dbb875a0da01 "XYZ" %}}) Log file for 2,000 step mode II (shear run).

CMDF - xyz file - mode II, shear ({{% resource_link 3539024b-0910-7b50-93ba-423ff45100f5 "XYZ" %}}) This .xyz file shows a sequence of 2,000 steps under shear loading. Frequency of snapshot writing, time step etc. is the same in all examples, and equal to the example script.

NAMD - Initial geometry for pulling ({{% resource_link 9f09def6-cd30-4e68-69cd-12246301ea47 "COOR" %}})

NAMD - tensile deformation 0.002 rate (F-x-curve) ({{% resource_link cf4b4a1c-ce39-d9c3-e689-a765055519f3 "JPG" %}})

NAMD - tensile deformation 0.001 rate ({{% resource_link 3d764ead-4ed4-e478-81d9-e696679c2e23 "DCD" %}})

NAMD - tensile deformation 0.0005 rate (F-x-curve) ({{% resource_link 47930739-3f61-efde-290f-df353e32561a "JPG" %}})

NAMD - tensile deformation 0.0005 rate ({{% resource_link a2aa2691-8504-797e-f418-424f2d03b12a "DCD" %}})

NAMD - bending load (force-displacement plot) ({{% resource_link b204751d-8c73-dbe8-ef0c-5fd16ea340c6 "JPG" %}})

NAMD - bending load ({{% resource_link a3975ff0-3fdb-b16e-5bc9-d0d1f4526203 "DCD" %}})

NAMD - tensile deformation 0.002 rate (data file for force-displacement plot) ({{% resource_link 497d53a5-ffc9-94b1-5148-dcacf3277333 "DAT" %}}) NOTE: Order of columns: Displacement (in Angstrom), force (in pN). This applies to all .dat files.

NAMD - tensile deformation 0.001 rate (data file for force-displacement plot) ({{% resource_link 2b4e680e-0d89-c17e-97f2-4a68277f1864 "DAT" %}})

NAMD - tensile deformation 0.0005 rate (data file for force-displacement plot) ({{% resource_link 9503dc85-1c4a-385b-9059-13db73a5eb52 "DAT" %}})

NAMD - bending deformation (data file for force-displacement plot) ({{% resource_link 1236a4ba-5bd4-4751-570f-d75163b7161e "DAT" %}})