# tanujchauhan17.github.io-SScalc

A sophisticated, high-precision astronomical tool that bridges the gap between modern scientific ephemeris models and the ancient Indian astronomical system, Surya Siddhanta.

This application provides real-time calculations for planetary positions, eclipses, Vedic horoscopes, and celestial visualizations using high-fidelity physics models.

**[🚀 Live Demo: Modern & Ancient Astronomical Calculator](https://tanujchauhan17.github.io/tanujchauhan17.github.io-SScalc/)**

---

## ✨ Key Features

### 1. Dual Astronomy Engines
* **Modern Engine:** Powered by the [astronomy-engine](https://github.com/cosinekitty/astronomy) library using VSOP87 (Planetary) and ELP2000 (Lunar) models for sub-arcsecond accuracy.
* **Ancient Engine:** A custom-built implementation of the Surya Siddhanta, calculating positions based on Ahargana (days elapsed since epoch) and ancient sine tables.

### 2. Live Interactive Visualizations
* **Local Sky Chart (Horizon):** A real-time 2D projection of the sky from your location. Includes constellations, zodiac signs, and planetary positions with zoom and pan capabilities.
* **Solar System View:** A top-down heliocentric view of the solar system (Logarithmic and True Scale modes).

### 3. Vedic Astrology & Cultural Dashboard
* **Horoscope Generation:** Supports both North Indian and South Indian chart styles.
* **Panchang Elements:** Real-time calculation of Tithi, Paksha, Nakshatra, and Ayanamsha (Precession).
* **Festival Predictor:** Calculates dates for major Hindu festivals (Diwali, Holi, Navratri, etc.) based on lunar-solar alignments.
* **Planetary Status:** Detailed tracking of Combustion (Asth) and Retrograde (Vakri) motions.

### 4. Eclipse & Event Predictor
* **Global & Local Eclipses:** Predicts upcoming Solar and Lunar eclipses with local visibility checking.
* **Conjunctions & Occultations:** Scans the ephemeris for planetary alignments and lunar occultations.
* **Seasonal Events:** Tracks Equinoxes and Solstices.

---

## 🛠️ Technologies Used

* **HTML5 / CSS3:** Structured with [Tailwind CSS](https://tailwindcss.com/) for a responsive, modern UI.
* **JavaScript (ES6+):** Core logic for both astronomical engines.
* **HTML5 Canvas:** Used for rendering high-performance interactive sky and solar system maps.
* **Astronomy Engine JS:** Utilized for modern geocentric and heliocentric coordinate calculations.
* **Google Fonts:** [Inter font family](https://fonts.google.com/specimen/Inter) for high legibility.

---

## 📖 How to Use

1. **Set Location:** Choose a preset city or enter custom Latitude/Longitude.
2. **Select Date/Time:** Use the datetime picker or enable Real-time mode to watch the sky move in sync with the clock.
3. **Toggle Views:** * Use the "Switch to SS Calc" button to compare modern data with ancient Surya Siddhanta results.
   * Click "🔭 Live Sky & System" to open the visual maps.
   * Click "✨ Vedic & Festival Dashboard" for astrological insights.
4. **Explore Data:** Click on planetary rows in the "Mean Positions" table to see detailed info like Rise/Set times and upcoming conjunctions.

---

## 🧮 Accuracy & Models

* **Modern Data:** Based on J2000.0 epoch, accounting for nutation, aberration, and light-time correction.
* **Surya Siddhanta Data:** Derived from traditional parameters including the Bija corrections, providing a fascinating look at how ancient astronomers viewed the cosmos thousands of years ago.

---

## 📜 License

This project is open-source and available under the [MIT License](https://choosealicense.com/licenses/mit/).

---

## 🙌 Acknowledgments

* The [Astronomy Engine](https://github.com/cosinekitty/astronomy) by [Don Cross](https://github.com/cosinekitty) for the robust modern calculations.
* Ancient Indian mathematicians and astronomers for the foundational principles of the Surya Siddhanta.
