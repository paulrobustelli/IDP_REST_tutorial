# IDP Replica Exchange with Solute Tempering (REST2)  Simulation Tutorial
REST2 Enhanced Sampling Tutorial containing software installation instructions, post simulation analysis and tutorial files. 

File Tree:
```bash
.
├── INSTALLATION_INSTRUCTIONS
│   ├── README.md
│   ├── install.sh
│   └── setup_env.yml
├── LICENSE
├── POST_SIMULATION_ANALYSIS
│   ├── README.md
│   ├── demux.fix.pl
│   ├── make_demux.sh
│   └── reference_files
│       ├── README.md
│       ├── replica_index.n50.s0.-80.xvg
│       ├── replica_index.xvg
│       └── replica_temp.xvg
├── README.md
└── TUTORIAL_FILES
    ├── README.md
    ├── initial_input_files
    │   ├── README.md
    │   ├── processed.top
    │   └── prot_only.pdb
    ├── mdp_files
    │   ├── NPT0.mdp
    │   ├── NPT1.mdp
    │   ├── NVT.mdp
    │   ├── README.md
    │   ├── minimz.mdp
    │   └── prod.mdp
    ├── reference_files
    │   ├── README.md
    │   ├── equilibrated_configurations
    │   │   ├── 0.gro
    │   │   ├── 1.gro
    │   │   ├── 2.gro
    │   │   ├── 3.gro
    │   │   ├── 4.gro
    │   │   ├── 5.gro
    │   │   ├── 6.gro
    │   │   ├── 7.gro
    │   │   ├── 8.gro
    │   │   └── 9.gro
    │   ├── og_topology
    │   │   ├── REST.top
    │   │   └── processed.top
    │   ├── scaled_topologies
    │   │   ├── topol_0.top
    │   │   ├── topol_1.top
    │   │   ├── topol_2.top
    │   │   ├── topol_3.top
    │   │   ├── topol_4.top
    │   │   ├── topol_5.top
    │   │   ├── topol_6.top
    │   │   ├── topol_7.top
    │   │   ├── topol_8.top
    │   │   └── topol_9.top
    │   └── solvated_protein
    │       ├── solv_ions_0.gro
    │       ├── solv_ions_1.gro
    │       ├── solv_ions_2.gro
    │       ├── solv_ions_3.gro
    │       ├── solv_ions_4.gro
    │       ├── solv_ions_5.gro
    │       ├── solv_ions_6.gro
    │       ├── solv_ions_7.gro
    │       ├── solv_ions_8.gro
    │       └── solv_ions_9.gro
    └── run_md.sh
```

