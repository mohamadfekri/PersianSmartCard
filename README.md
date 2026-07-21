@'
# Smart Card Pro for Power BI

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)](https://powerbi.microsoft.com/)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

## 🚀 Smart Card Pro

Professional Power BI Custom Visual with Smart Unit Conversion and Trend Indicator

## ✨ Features

- ✅ **One Measure Only** - No complex DAX required
- ✅ **Smart Unit Conversion** - Automatic unit formatting
- ✅ **Trend Indicator** - Compare two values with visual icons (📈 📉 ➡️)
- ✅ **Bilingual Support** - Persian (فارسی) and English
- ✅ **Full Customization** - Prefix, Value, Suffix, Colors, Fonts
- ✅ **High Performance** - Render time under 20ms

## 📊 Data Roles

| Role | Type | Description |
|------|------|-------------|
| **Value** | Required | Main numeric value |
| **Comparison Value** | Optional | Value to compare for trend |
| **Tooltip** | Optional | Additional info on hover |

## 🎨 Customization

- **Prefix**: Text, Size, Color
- **Value**: Size, Color, Decimal Places, Thousand Separator
- **Suffix**: Off, Custom, Smart Unit (Currency, Time, Weight, Length, Data Size)
- **Trend**: Show/Hide, Icon Size, Colors (Up/Down/Equal)
- **Background**: Color, Radius, Shadow

## 📦 Installation

1. Download `.pbiviz` from [Releases](https://github.com/mohamadfekri/PersianSmartCardPro/releases)
2. Import into Power BI Desktop

## 🛠️ Development

```bash
git clone https://github.com/mohamadfekri/PersianSmartCardPro.git
cd PersianSmartCardPro
npm install
pbiviz package
