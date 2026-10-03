# TPM3D SLS Engineering Resources

Practical documentation and a browser-based mass estimator for engineers preparing SLS nylon projects. Published 3 October 2026.

## Start here

- **Estimate weight:** [Open the browser calculator](https://pacodeng84-ship-it.github.io/tpm3d-sls-engineering-resources/).
- **Compare candidates:** [Use the PA11 / PA12 selection worksheet](docs/material-selection.md).
- **Prepare an RFQ:** [Review finishing and design inputs](docs/finishing-design.md).
- **Compare processes:** [Read the SLS vs SLA engineering selection guide on DEV.to](https://dev.to/rongdong_deng_259145a94b1/build-a-unit-safe-sls-part-weight-estimator-in-javascript-40p4).

For engineers, product teams and buyers preparing functional nylon prototypes or low-volume SLS projects.

## Use the calculator

Open `index.html` in a browser. No installation, external dependencies, CAD upload or tracking scripts are required. Enter the **actual solid material volume**, unit, grade-specific density and quantity. The tool does not infer volume from STL or STEP files.

### Quick example

1. Enter `100` as volume and choose `cm³`.
2. Choose the Precimid 1176Pro PA12 preset, or enter a confirmed custom density.
3. Enter `10` as quantity and click **Estimate weight**.
4. Check the result: **95 g per part, 950 g per batch**.

Entering `100000` with `mm³` produces the same result. For hollow or lattice parts, use the final solid material volume after subtracting voids.

### What the result covers

The estimate covers material mass. It excludes coatings, inserts, residual powder, packaging and shipping. It does not calculate price or lead time. Formal quotation requires CAD, material grade, quantity, finish and inspection requirements.

The two named density presets are owner-supplied figures, not independently verified public TDS data. Custom density is the default. Confirm the current density for the exact grade and manufacturing state.

## Engineering documents

- [PA11 and PA12 selection worksheet](docs/material-selection.md)
- [Finishing and design handoff checklist](docs/finishing-design.md)

## Official resources

- [TPM3D PA11](https://www.sls-3d.com/materials/pa11?utm_source=github&utm_medium=referral&utm_campaign=sls_engineering_resources&utm_content=readme_pa11)
- [TPM3D PA12](https://www.sls-3d.com/materials/pa12?utm_source=github&utm_medium=referral&utm_campaign=sls_engineering_resources&utm_content=readme_pa12)
- [SLS services](https://www.sls-3d.com/services?utm_source=github&utm_medium=referral&utm_campaign=sls_engineering_resources&utm_content=readme_services)
- [Discuss Your Application](https://www.sls-3d.com/quote?utm_source=github&utm_medium=referral&utm_campaign=sls_engineering_resources&utm_content=readme_quote)

## Online calculator

[Open the online SLS Part Weight Estimator](https://pacodeng84-ship-it.github.io/tpm3d-sls-engineering-resources/).

Hosted on GitHub Pages and verified on 3 October 2026: unit conversion, named density presets and batch calculations. The calculator source is `index.html`.

## License

Copyright 2026 TPM3D. All rights reserved. No open-source redistribution license has been assigned.
