# X3DNA-DSSR: Structural Bioinformatics of Nucleic Acids

Welcome to the **X3DNA-DSSR** GitHub organization. Supported by NIH/NIGMS grant **R24GM153869**, this platform serves as an open National Resource for the analysis, modeling, and visualization of 3D nucleic acid structures (DNA, RNA, and their complexes).

---

## Software Lineage

**SCHNAarP** (1997) &rarr; **3DNA v1.5** (2003) &rarr; **3DNA v2.4** (2008) &rarr; **DSSR** (2015) &rarr; **wDSSR** (2026)

* **SCHNAarP** — Foundational CEHS matrix calculation scheme and global helical parameter definitions.
* **3DNA v1.5** — Standard base reference frame adoption and initial integrated software package.
* **3DNA v2.4** — Definitive classic suite with fiber models, "simple" parameters, and *Nature Protocols* recipes.
* **DSSR** — Next-generation computational engine for dissecting the spatial structure of RNA and DNA.
* **wDSSR** — Streamlined web interface providing an interactive 7-module scientific workflow.

---

## Obtaining DSSR (Command-Line Executable)

While **wDSSR** offers a registration-free web experience and **dssr-pymol** provides an interactive PyMOL interface, the underlying standalone **DSSR** (`x3dna-dssr`) engine is distributed as a self-contained, high-performance command-line binary for Linux, macOS, and Windows.

### Latest Release: DSSR v2.9.4

As of DSSR v2.0, the command-line executable is licensed and distributed by Columbia Technology Ventures (CTV, CU20391). Our goal is to keep DSSR always available to academic users. DSSR completely supersedes 3DNA v2.4, featuring vastly expanded structural analysis capabilities, context-sensitive base mutation, fiber modeling, and high-throughput JSON output.

* **Academic Users:** Submit an electronic license request for **DSSR** by selecting **"Express Licensing"** on the [Columbia Technology Ventures (CTV) DSSR Portal](https://innovation.columbia.edu/technologies/CU20391).
* **Commercial Users:** Inquire about pricing and commercial licensing terms by contacting CTV at `techtransfer@columbia.edu`, copying `xiangjun@x3dna.org`.
* **User Manual:** Download the comprehensive [DSSR User Manual (PDF)](https://docs.x3dna-dssr.org/dssr-manual.pdf).
* **Video Overview:** Watch the recorded [DSSR Video Overview](https://youtu.be/5SJxjBDob9U) on YouTube for an introduction to core features and algorithms.

### Legacy Pre-Licensing Release: DSSR v1.9.10

For historical reproduction, or for researchers in regions and institutions where obtaining a CTV license is restricted or unavailable due to institutional licensing policies, the pre-licensing release **v1.9.10** (accompanying the 2020 *Nucleic Acids Research* DSSR-PyMOL publication) remains freely downloadable and works well, including with the new DSSR-PyMOL plugin:

* [Linux (x86_64)](https://docs.x3dna-dssr.org/download.php?pkg=linux) (`DSSR-v1.9.10-linux.zip`)
* [macOS](https://docs.x3dna-dssr.org/download.php?pkg=macos) (`DSSR-v1.9.10-macos.zip`)
* [Windows](https://docs.x3dna-dssr.org/download.php?pkg=windows) (`DSSR-v1.9.10-windows.zip`)

*(Note: In addition to the v1.9.10 standalone executables, the registration-free web servers [wDSSR](https://web.x3dna-dssr.org/) and [DSSR-PyMOL schematics](https://skmatic.x3dna-dssr.org/) are globally accessible without regional or licensing restrictions.)*

---

## Repositories & Tools

### Active & Modern Platforms
* **[wDSSR](https://github.com/x3dna-dssr/wDSSR)** — Next-generation web server ([web.x3dna-dssr.org](https://web.x3dna-dssr.org)) providing an intuitive 7-module scientific workflow: `Analyze`, `Rebuild`, `Model`, `Circularize`, `Mutate`, `Assemble`, and `Visualize`.
* **[dssr-pymol](https://github.com/x3dna-dssr/dssr-pymol)** — Integrated PyMOL plugin bridging stylized 3D cartoon-block representations with an interactive pure-Python RNA 2D layout studio.

### Classic & Archival Foundations
* **[3DNA v2.4](https://github.com/x3dna-dssr/x3dna-v2.4)** — Final release of the classic 3DNA suite (v2.4.9), featuring rigid-body parameter analysis, "simple" base-pair/step parameters, 55 fiber models, and reproducible recipes. *(Maintained for bug fixes; superseded by DSSR).*
* **[3DNA v1.5](https://github.com/x3dna-dssr/x3dna-v1.5)** — Foundational 2003 *NAR* release implementing the IUBMB/IUPAC standard base reference frame; preserved for historical reference and pipelines relying on v1.5 algorithms.
* **[SCHNAarP](https://github.com/x3dna-dssr/SCHNAarP)** — Foundational C implementation of the CEHS matrix scheme and global helical parameters.

---

## Community & Support

* **Central Forum:** Visit [GitHub Discussions](https://github.com/orgs/x3dna-dssr/discussions) to ask questions, report unexpected results, and share ideas across all tools.
* **Legacy Archive:** Historical forum threads (2011–2026) remain searchable at the read-only [3DNA Forum](http://forum.x3dna.org/).

---

## Funding & Citation

The X3DNA-DSSR project is supported by the National Institute of General Medical Sciences of the National Institutes of Health under Award Number **R24GM153869**. If you use these tools, please cite the corresponding publications listed in each repository's `CITATION.cff` and `README.md`.
