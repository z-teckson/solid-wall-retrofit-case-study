# Baseline Conditions: Existing Solid Brick Wall

## Construction Description

The wall is a typical solid brick construction found in UK housing built before 1920. It consists of:

- **External finish**: 105 mm facing brick (λ ≈ 0.84 W/mK).
- **Mortar joints**: Lime‑based mortar (λ ≈ 0.80 W/mK).
- **Internal finish**: 12 mm lime plaster (λ ≈ 0.70 W/mK).

No cavity, no insulation.

## Thermal Performance

### Layer Resistances

| Layer | Thickness (m) | Conductivity (W/mK) | Resistance (m²K/W) |
|-------|---------------|---------------------|-------------------|
| External surface | – | – | 0.04 (Rse) |
| Brickwork | 0.105 | 0.84 | 0.125 |
| Mortar (approx.) | – | – | (included in brickwork) |
| Internal plaster | 0.012 | 0.70 | 0.017 |
| Internal surface | – | – | 0.13 (Rsi) |

**Total resistance** Rtotal = Rse + Rbrick + Rplaster + Rsi = 0.04 + 0.125 + 0.017 + 0.13 = 0.312 m²K/W.

**U‑value** = 1 / Rtotal = 1 / 0.312 ≈ **3.21 W/m²K**.

*Note: This is a simplified calculation; actual in‑situ U‑values can be higher due to moisture, air infiltration, and mortar bridges.*

## Assumptions

- Steady‑state conditions, no dynamic effects.
- Surface resistances according to ISO 6946.
- Brick conductivity taken from typical values for dense clay brick.

## References

- BRE Digest 108 (U‑values of traditional walls).
- PHPP manual Appendix 1 (default material conductivities).
