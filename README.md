# 🔬 Teleparallel Holoscreen Laboratory v1.0

**A Controlled Comparative Apparatus for Testing TEGR vs GR Near Event Horizons**

-----

## What This Is

A **laboratory-grade falsification instrument** that implements two competing theories of gravity:

1. **TEGR (Teleparallel)** — Weitzenböck connection with torsion, zero curvature
1. **GR (Standard)** — Levi-Civita connection with curvature, zero torsion

Both theories run on:

- Same numerical solver (TVD-limited PDE)
- Same boundary conditions
- Same experimental protocols
- Same statistical analysis

**Key Innovation:** Toggle between frameworks → direct falsification testing.

-----

## Quick Start

```bash
# Open in browser
open holoscreen_tegr_lab_final.html

# Or just double-click the file
```

See `QUICKSTART.md` for 30-second usage guide.

-----

## Files Included

|File                            |Purpose                                           |
|--------------------------------|--------------------------------------------------|
|`holoscreen_tegr_lab_final.html`|**Main application** (standalone, no dependencies)|
|`QUICKSTART.md`                 |Immediate usage guide                             |
|`HOLOSCREEN_SCIENTIFIC_NOTES.md`|Complete technical documentation                  |
|`README.md`                     |This file                                         |

-----

## Core Features

### ✅ Theoretical Rigor

- Complete TEGR formulation (torsion tensor, contorsion, superpotential)
- Proper field equations displayed
- Framework toggle for direct comparison

### ✅ Experimental Protocols

- QED beta function recovery validation
- Double-slit interferometry falsification
- Gauge-invariant boundary observables
- Automated parameter sweeps

### ✅ Scientific Honesty

- Statistical disclaimers throughout
- Known limitations documented
- Phenomenological models clearly labeled
- No overclaiming

### ✅ Data Reproducibility

- JSON export (full dataset with metadata)
- CSV export (time series for analysis)
- TXT report (falsification summary)
- Sweep data (automated experiments)

-----

## What Makes This Different

Most gravitational simulations are:

- ❌ Single-theory implementations
- ❌ Post-hoc analysis
- ❌ Opaque numerical methods

This apparatus is:

- ✅ **Dual-theory** with shared numerics
- ✅ **Real-time** comparative falsification
- ✅ **Transparent** PDE solver + stability monitoring

-----

## Scientific Status

### What This Can Do

- Test TEGR predictions against GR in controlled setting
- Validate QED preservation (consistency check)
- Generate falsifiable interferometry predictions
- Export publication-ready datasets

### What This Cannot Do

- ❌ Prove TEGR is correct (only data can do that)
- ❌ Replace real experiments (this is simulation)
- ❌ Perform rigorous statistical tests (χ² are proxies)
- ❌ Model full 3+1D quantum gravity

See `HOLOSCREEN_SCIENTIFIC_NOTES.md` → “Known Limitations” for details.

-----

## Use Cases

### 1. Graduate Education

- Teaching TEGR vs GR differences
- Exploring boundary conditions in curved spacetime
- Hands-on falsification methodology

### 2. Research Exploration

- Parameter space exploration for TEGR
- Identifying experimentally testable predictions
- Preliminary design for real experiments

### 3. Publication Support

- Supplementary material for theory papers
- Interactive demonstration of falsification protocols
- Reproducible numerical methods

-----

## System Requirements

**Minimum:**

- Modern browser (Chrome 90+, Firefox 88+, Safari 14+)
- 100 MB RAM
- 1280×720 display

**Recommended:**

- Chrome 120+ for best performance
- 4 GB RAM for large sweeps
- 1920×1080+ for comfortable viewing

**No installation required** — just open HTML file.

-----

## Authors

- **James Lockwood** — TEGR formulation, theoretical framework
- **Sheldon Lindberg** — PDE implementation, numerical methods
- **Christopher Cyrek** — Experimental protocols, validation
- **Derek Burkeen** — Statistical analysis, data export

-----

## Citation

```bibtex
@software{holoscreen2026,
  title = {Teleparallel Holoscreen Laboratory: A Falsification Apparatus for TEGR},
  author = {Lockwood, James and Lindberg, Sheldon and Cyrek, Christopher and Burkeen, Derek},
  year = {2026},
  version = {1.0.0-laboratory},
  url = {https://example.com/holoscreen}
}
```

-----

## What Would Falsify TEGR?

### Decisive Tests

1. **QED violation:** `|Δα⁻¹| > 0.5` at Z-boson scale
1. **Negative Δχ²:** QM consistently better than TEGR
1. **Gauge failure:** {θ, q_Δ} ≪ 2π systematically
1. **Boundary pathology:** Unphysical field discontinuities

### Experimental Requirements

- High-precision electron interferometry near massive objects
- Josephson arrays in strong gravitational gradients
- Multi-scale torsion correlation measurements

-----

## Known Issues & Limitations

### Theoretical

- Field is classical (no quantum gravity)
- Schwarzschild only (no rotation/charge)
- Phenomenological bracket (not derived)

### Numerical

- 1D spatial grid (full 3+1D too expensive)
- Reference data is synthetic (needs real experiments)
- Grid resolution may under-resolve near-horizon

### Statistical

- χ² tests are heuristic proxies only
- No systematic uncertainties modeled
- Single realization (no ensemble)

**See full documentation for mitigation strategies.**

-----

## License & Terms

This software is provided **as-is** for research and education.

**You may:**

- ✅ Use for research and teaching
- ✅ Modify and extend
- ✅ Cite in publications

**You must:**

- 📖 Cite original authors
- ⚠️ Include statistical disclaimers when publishing results
- 🔬 Validate independently with real data

**You may not:**

- ❌ Claim this constitutes experimental proof
- ❌ Remove authorship attribution
- ❌ Misrepresent statistical rigor

-----

## Changelog

### v1.0.0-laboratory (2026-01-12)

**Initial release — laboratory-grade falsification apparatus**

**Major Features:**

- TEGR/GR framework toggle
- Complete torsion tensor formulation
- Gauge-invariant boundary observables
- QED recovery validation
- Double-slit falsification protocol
- Automated experimental sweeps
- Comprehensive data export

**Quality Improvements:**

- Statistical disclaimers throughout
- PDE stability auto-recovery
- Input sanitization layer
- Interactive tooltips
- Publication-ready exports

-----

## Getting Help

**Quick questions:** See `QUICKSTART.md`  
**Technical details:** See `HOLOSCREEN_SCIENTIFIC_NOTES.md`  
**Bug reports:** GitHub issues (or email authors)

-----

## Next Steps

### If You’re New

1. Read `QUICKSTART.md` (5 minutes)
1. Open HTML file, toggle frameworks, watch field evolve
1. Run a Γ scan experiment
1. Export data and explore

### If You’re Experienced

1. Read `HOLOSCREEN_SCIENTIFIC_NOTES.md` (30 minutes)
1. Verify numerical stability for your use case
1. Replace `REF_DATA` with real experimental results
1. Run systematic validation campaign

### If You Want to Contribute

1. Fork/extend the PDE solver
1. Add new experimental protocols
1. Implement 2D/3D spatial grids
1. Integrate with real laboratory instruments

-----

## Final Notes

This apparatus represents **months of careful design** to achieve:

- **Scientific rigor** without overclaiming
- **Numerical transparency** without sacrificing performance
- **Experimental realism** without requiring equipment

It is **not perfect** — but it is **honest, testable, and reproducible**.

Use it to explore. Use it to teach. Use it to falsify.

That’s what science is.

-----

**Version:** 1.0.0-laboratory  
**Released:** January 2026  
**Status:** Laboratory-grade research tool

🔬 **Happy Testing!**
