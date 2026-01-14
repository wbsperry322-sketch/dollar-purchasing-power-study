# Dollar Purchasing Power Study - Calculations Verification

## Base Values (1970)

| Category | 1970 Value | 2024 Value | Growth Multiple | % Growth | Annual Rate |
|----------|------------|------------|-----------------|----------|-------------|
| **Assets** | | | | | |
| - Stocks | 0.70T | 62.00T | 88.6x | 8,757% | 8.4%/year |
| - Bonds | 0.40T | 55.00T | 137.5x | 13,650% | 9.5%/year |
| - Housing | 1.00T | 50.00T | 50.0x | 4,900% | 7.5%/year |
| - Private Co. | 0.30T | 20.00T | 66.7x | 6,567% | 8.0%/year |
| **TOTAL ASSETS** | **2.40T** | **187.00T** | **77.92x** | **7,692%** | **8.15%/year** |
| | | | | | |
| **Consumer Spending** | | | | | |
| - Food | 0.12T | 2.58T | 21.5x | 2,050% | 5.8%/year |
| - Services | 0.15T | 13.00T | 86.7x | 8,567% | 8.4%/year |
| - Energy | 0.08T | 1.20T | 15.0x | 1,400% | 5.1%/year |
| - Automotive | 0.04T | 1.00T | 25.0x | 2,400% | 6.1%/year |
| - Other Goods | 0.10T | 3.50T | 35.0x | 3,400% | 6.8%/year |
| **TOTAL CONSUMER** | **0.49T** | **21.28T** | **43.43x** | **4,243%** | **7.2%/year** |
| | | | | | |
| **Money Supply & GDP** | | | | | |
| M2 | 0.60T | 21.30T | 35.50x | 3,450% | 6.75%/year |
| M0 | 0.08T | 5.80T | 72.50x | 7,150% | 8.18%/year |
| GDP | 1.07T | 29.00T | 27.10x | 2,610% | 6.18%/year |

## Key Ratios

| Comparison | Calculation | Result |
|------------|-------------|--------|
| Assets vs GDP | 77.92x / 27.10x | **2.88x faster** |
| Assets vs CPI | 77.92x / 8x | **9.74x faster** |
| M2 vs GDP | 35.50x / 27.10x | **1.31x faster** |
| M0 vs GDP | 72.50x / 27.10x | **2.68x faster** |

## Summary Card Verification

### Current Site Values:
- ✅ CPI: ~700% (~8x | ~3.9%/year)
- ✅ GDP: ~2,600% (~27x | ~6.3%/year) - *Should be 6.2%/year*
- ✅ M2: ~3,450% (~35.5x | ~6.8%/year)
- ✅ M0: ~7,150% (~73x | ~8.2%/year)
- ✅ Assets: ~7,700% (~78x | ~8.2%/year) - *Should be 8.15%/year rounds to 8.2%*

### Narrative Text Check:
Current: "Total assets grew 78x while GDP grew 27x (2.9x faster). Assets grew 9x faster than reported CPI inflation."

Calculations:
- 78x / 27x = 2.89x ✅ (rounds to 2.9x)
- 78x / 8x = 9.75x ⚠️ (should be "~10x faster" not "9x faster")

## Issues Found:

1. ⚠️ **Assets vs CPI ratio is wrong**: Should be "~10x faster" not "9x faster"
   - Calculation: 77.92x / 8x = 9.74x → rounds to 10x

2. ⚠️ **GDP annual rate slightly off**: Shows 6.3%/year but actual is 6.18%/year (rounds to 6.2%/year)

## All Calculations Match:
- ✅ Total Assets: 2.40T → 187T = 78x growth
- ✅ M2: 0.60T → 21.30T = 35.5x growth
- ✅ M0: 0.08T → 5.80T = 73x growth (rounded from 72.5x)
- ✅ GDP: 1.07T → 29.00T = 27x growth
- ✅ Assets/GDP ratio: 2.9x faster
