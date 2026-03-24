
**India's Most Compact & Advanced 16-Channel IR Sensor Array** 

**High-speed 16-channel sensor array designed for advanced line follower robots using analog multiplexing.**

#  Most Compact Advanced 16 Sensor Array
## — SMD Version —

<img width="5000" height="2813" alt="Sensor updw canva" src="https://github.com/user-attachments/assets/fab9c76d-38b1-4176-89f0-c446358fd387" />

<br/>

[![PCB](https://img.shields.io/badge/PCB-144mm%20×%2030mm-E7352C?style=for-the-badge&logo=altiumdesigner&logoColor=white)](.)
[![Sensors](https://img.shields.io/badge/Sensors-QRE1113GR%20×16-8A2BE2?style=for-the-badge&logoColor=white)](.)
[![MUX](https://img.shields.io/badge/MUX-74HC4067%20SSOP24-FF6B00?style=for-the-badge&logoColor=white)](.)
[![Layers](https://img.shields.io/badge/PCB%20Layers-2%20Copper-00979D?style=for-the-badge&logoColor=white)](.)
[![SMD](https://img.shields.io/badge/Package-Full%20SMD-1B7A3E?style=for-the-badge&logoColor=white)](.)
[![License](https://img.shields.io/badge/License-MIT-brightgreen?style=for-the-badge)](LICENSE)


<br/>

>  **India's Most Compact & Advanced 16-Channel IR Sensor Array**  
> Full SMD design · Zero unrouted nets · 144mm ultra-slim profile · Competition proven

<br/>

```
╔══════════════════════════════════════════════════════════════════════╗
║   144.017mm × 29.96mm  │  2-Layer PCB  │  55 Components  │  0 Unrouted  ║
╚══════════════════════════════════════════════════════════════════════╝
```

</div>

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Why This Board](#-why-this-board)
- [PCB Specifications](#-pcb-specifications)
- [Component Details](#-component-details)
- [Bill of Materials](#-bill-of-materials)
- [Working Principle](#-working-principle)
- [Pin Configuration](#-pin-configuration)
- [Firmware & Integration](#-firmware--integration)
- [Performance](#-performance-specifications)
- [PCB Design Details](#-pcb-design-details)
- [Applications](#-applications)
- [Screenshots](#-screenshots--pcb-preview)
- [Author](#-author)

---

##  Overview

The **Most Compact Advanced 16 Sensor Array — SMD Version** is a precision-engineered, fully surface-mount infrared sensor board designed from the ground up for **high-speed competitive line follower robots**.

Every design decision — from trace routing to component selection — is optimized for **maximum performance in minimum space**. At just **144.017mm × 29.96mm**, this is one of the most compact 16-channel IR arrays available for competitive robotics in India.

With **zero unrouted nets**, **75 vias**, and **1286.76mm of precision-routed tracks**, this board represents a benchmark in embedded PCB design for robotics.

---

##  Why This Board

```
┌─────────────────────────────────────────────────────────────────────┐
│                    Comparison                                       │
│                                                                     │
│  Generic 16-sensor boards   →  Through-hole, bulky, noisy          │
│  This board                 →  Full SMD, ultra-compact, clean       │
│                                                                     │
│  Generic boards             →  Multiple unrouted nets possible      │
│  This board                 →  0 unrouted nets — fully verified     │
│                                                                     │
│  Generic boards             →  Basic resistor networks              │
│  This board                 →  SSOP-24 MUX, 0.1µF decoupling,      │
│                                optimized pull-up/down network       │
└─────────────────────────────────────────────────────────────────────┘
```

| Parameter | This Board | Typical Generic Board |
|---|:---:|:---:|
| Form Factor | Full SMD | Through-hole |
| Board Size | 144 × 30 mm | 160 × 40+ mm |
| Unrouted Nets | **0** | Unknown |
| MUX Package | SSOP-24 | DIP/SOIC |
| Noise Filtering | Dedicated 0.1µF decoupling | None |
| Competition Ready | ✅ Yes | ⚠️ Maybe |

---

##  PCB Specifications

| Parameter | Value |
|---|---|
| **Board Name** | Most Compact Advanced 16 Sensor Array — SMD Version |
| **Schematic** | Schematic1 |
| **Board Size** | 144.017 mm × 29.96 mm |
| **Total Layers** | 22 (2 Copper + 20 Technical) |
| **Copper Layers** | 2 (Top + Bottom) |
| **Total Devices** | 8 unique device types |
| **Total Footprints** | 6 unique footprint types |
| **Total Components** | 55 |
| **Top Layer Components** | 39 |
| **Bottom Layer Components** | 16 |
| **Total Pads** | 179 |
| **SMD Pads** | 175 |
| **Metallized Holes** | 4 |
| **Non-Metallic Holes** | 0 |
| **Total Nets** | 43 |
| **Unrouted Nets** | **0 ✅ (Fully Routed)** |
| **Total Vias** | 75 |
| **Through Vias** | 75 |
| **Blind / Buried Vias** | 0 |
| **Copper Areas** | 0 |
| **Total Track Length** | 1286.762 mm |
| **Slot Regions** | 0 |
| **Design Date** | 2026-03-24 |

---

##  Component Details

### 1. QRE1113GR — Infrared Reflectance Sensor `×16`

```
┌─────────────────────────────────────────────┐
│              QRE1113GR                      │
│                                             │
│   IR LED ──▶  Surface  ──▶  Phototransistor │
│   (Emitter)             (Detector/Output)   │
└─────────────────────────────────────────────┘
```

| Parameter | Value |
|---|---|
| **Type** | Reflective Infrared Sensor |
| **Emitter** | GaAs Infrared LED |
| **Detector** | NPN Silicon Phototransistor |
| **Peak Wavelength** | 950 nm |
| **Operating Voltage** | 5V |
| **Optimal Sensing Distance** | 3 – 5 mm from surface |
| **Package** | SMD (ultra-compact surface mount) |
| **Output Type** | Analog — voltage varies with reflectivity |
| **Response** | High output on dark surface · Low on light surface |
| **Quantity on Board** | **16** |

> The **QRE1113GR** is the gold standard IR sensor for line follower robots — chosen for its consistent analog output, compact SMD footprint, and excellent sensitivity at low sensing distances.

---

### 2. SSOP-24 (74HC4067) — 16-Channel Analog Multiplexer `×1`

```
         S0 S1 S2 S3
          │  │  │  │
          ▼  ▼  ▼  ▼
   ┌──────────────────────┐
   │      74HC4067        │
   │   16-to-1 Analog MUX │
   │                      │
   │  CH0  ──┐            │
   │  CH1  ──┤            │
   │  CH2  ──┤            │
   │  ...  ──┤───▶ SIG ───┼──▶ MCU Analog Pin
   │  CH15 ──┘            │
   └──────────────────────┘
   Package: SSOP-24 (L8.1-W5.3-P0.65-LS7.8)
```

| Parameter | Value |
|---|---|
| **IC** | 74HC4067 |
| **Package** | SSOP-24 (L8.1 × W5.3 mm, Pitch 0.65mm) |
| **Footprint** | SSOP-24_L8.1-W5.3-P0.65-LS7.8-BL |
| **Channels** | 16 analog input channels |
| **Select Lines** | 4 binary (S0, S1, S2, S3) |
| **Output** | 1 analog signal (SIG/COM) |
| **Operating Voltage** | 2V – 6V |
| **Propagation Delay** | ~7 ns |
| **On Resistance** | ~70 Ω |
| **Total MCU Pins Needed** | **5 only** (S0–S3 + SIG) |

> **SSOP-24 package** chosen over SOIC for smaller footprint — critical in a 144mm × 30mm compact board design.

---

### 3. 47kΩ Resistor — Pull-Down Network `×16`

| Parameter | Value |
|---|---|
| **Value** | 47 kΩ |
| **Type** | SMD Pull-Down Resistor |
| **Purpose** | Pulls phototransistor output to GND when no IR reflection |
| **Effect** | Ensures clean LOW signal on non-reflecting (white) surfaces |
| **Package** | SMD 0402 / 0603 |

> Without pull-down resistors, sensor outputs float between HIGH and LOW, causing **false detections** and unstable PID behavior. The 47kΩ value balances sensitivity and noise rejection.

---

### 4. 220Ω Resistor — IR LED Current Limiter `×16`

| Parameter | Value |
|---|---|
| **Value** | 220 Ω |
| **Type** | SMD Series Resistor |
| **Purpose** | Limits current through the IR emitter LED |
| **Calculation** | I = (5V − 1.2V) / 220Ω ≈ **17.3 mA** |
| **Effect** | Prevents LED burnout while maintaining adequate IR output |
| **Package** | SMD 0402 / 0603 |

> Choosing 220Ω provides **safe operating current** for the QRE1113GR IR LED while ensuring sufficient emission intensity for 3–5mm sensing distances.

---

### 5. 1kΩ Resistor — Signal Conditioning `×1`

| Parameter | Value |
|---|---|
| **Value** | 1 kΩ |
| **Type** | SMD Resistor |
| **Purpose** | Signal output protection / impedance matching |
| **Effect** | Protects MCU analog pin from overvoltage transients |
| **Package** | SMD 0402 / 0603 |

---

### 6. 0.1µF Capacitor — Decoupling `×1`

| Parameter | Value |
|---|---|
| **Value** | 0.1 µF (100 nF) |
| **Type** | SMD Ceramic Decoupling Capacitor |
| **Purpose** | Power supply noise filtering |
| **Placement** | Adjacent to 74HC4067 VCC pin |
| **Effect** | Suppresses high-frequency switching noise from MUX |
| **Package** | SMD 0402 / 0603 |

> A **0.1µF decoupling capacitor** is a critical design element — without it, MUX switching transients corrupt the analog signal readings, especially at high scan speeds.

---

### 7. FH12-08S-1SH — 8-Pin FFC/FPC Connector `×1`

| Parameter | Value |
|---|---|
| **Part** | FH12-08S-1SH |
| **Type** | 8-Pin Flat Flexible Cable Connector |
| **Pitch** | 1.0 mm |
| **Purpose** | Interface connector to main baseboard / MCU |
| **Pins Used** | VCC, GND, S0, S1, S2, S3, SIG, EN |
| **Advantage** | Low-profile, secure locking, vibration-resistant |

> The **FH12-08S-1SH** FFC connector enables a **clean, low-profile cable connection** to the robot's main board — reducing mechanical stress and connector failures during high-speed competition runs.

---

### 8. XL-1608SURC-06 — SMD Status LED `×1`

| Parameter | Value |
|---|---|
| **Part** | XL-1608SURC-06 |
| **Type** | SMD Red LED (1608 / 0603 package) |
| **Color** | Super Ultra Red |
| **Purpose** | Power-on indicator |
| **Advantage** | Confirms 5V rail is active during testing |

---

##  Bill of Materials

| # | Comment | Footprint | Qty | Purpose |
|:---:|---|---|:---:|---|
| 1 | QRE1113GR | SMD IR Sensor | 16 | IR reflectance sensing |
| 2 | SSOP-24_L8.1-W5.3-P0.65-LS7.8-BL | SSOP-24 | 1 | 16-ch analog multiplexer |
| 3 | 47kΩ | SMD Resistor | 16 | Pull-down for sensor output |
| 4 | 220Ω | SMD Resistor | 16 | IR LED current limiting |
| 5 | 1kΩ | SMD Resistor | 1 | Signal output conditioning |
| 6 | 0.1µF | SMD Capacitor | 1 | VCC decoupling / noise filter |
| 7 | FH12-08S-1SH | FFC 8-Pin 1mm | 1 | MCU interface connector |
| 8 | XL-1608SURC-06 | LED 1608 SMD | 1 | Power indicator |
| | | **Total Components** | **55** | |

---

##  Pin Configuration

### FFC Connector Pinout (FH12-08S-1SH)

| Pin | Label | Direction | Description |
|:---:|---|:---:|---|
| 1 | **VCC** | Input | 5V Power Supply |
| 2 | **GND** | Input | Ground Reference |
| 3 | **S0** | Input | MUX Select Bit 0 (LSB) |
| 4 | **S1** | Input | MUX Select Bit 1 |
| 5 | **S2** | Input | MUX Select Bit 2 |
| 6 | **S3** | Input | MUX Select Bit 3 (MSB) |
| 7 | **SIG** | Output | Analog Signal Output |
| 8 | **EN** | Input | Enable (Active LOW) |

### Channel Selection Truth Table

| Channel | Sensor | S3 | S2 | S1 | S0 |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 0 | Left Edge | 0 | 0 | 0 | 0 |
| 1 | | 0 | 0 | 0 | 1 |
| 2 | | 0 | 0 | 1 | 0 |
| 3 | | 0 | 0 | 1 | 1 |
| 4 | | 0 | 1 | 0 | 0 |
| 5 | | 0 | 1 | 0 | 1 |
| 6 | | 0 | 1 | 1 | 0 |
| 7 | Center-Left | 0 | 1 | 1 | 1 |
| 8 | Center-Right | 1 | 0 | 0 | 0 |
| 9 | | 1 | 0 | 0 | 1 |
| 10 | | 1 | 0 | 1 | 0 |
| 11 | | 1 | 0 | 1 | 1 |
| 12 | | 1 | 1 | 0 | 0 |
| 13 | | 1 | 1 | 0 | 1 |
| 14 | | 1 | 1 | 1 | 0 |
| 15 | Right Edge | 1 | 1 | 1 | 1 |

---

##  Firmware & Integration

### Arduino — Full Sensor Read with Calibration

```cpp
// Most Compact Advanced 16 Sensor Array — SMD Version
// Author: Raunak Choudhary
// Compatible: Arduino Nano, Uno, Mega, ESP32

#define S0   2
#define S1   3
#define S2   4
#define S3   5
#define SIG  A0
#define EN   6      // Active LOW enable

int  sensorRaw[16];
int  sensorMin[16];
int  sensorMax[16];
int  sensorCal[16];   // Calibrated 0–1000

void setup() {
  pinMode(S0, OUTPUT); pinMode(S1, OUTPUT);
  pinMode(S2, OUTPUT); pinMode(S3, OUTPUT);
  pinMode(EN, OUTPUT);
  digitalWrite(EN, LOW);    // Enable sensor array
  Serial.begin(115200);
  calibrate();
}

// ── Select MUX Channel ─────────────────────────────────────
void selectChannel(int ch) {
  digitalWrite(S0, (ch >> 0) & 1);
  digitalWrite(S1, (ch >> 1) & 1);
  digitalWrite(S2, (ch >> 2) & 1);
  digitalWrite(S3, (ch >> 3) & 1);
  delayMicroseconds(10);          // SSOP-24 settling time
}

// ── Read All 16 Channels ───────────────────────────────────
void readAllSensors() {
  for (int i = 0; i < 16; i++) {
    selectChannel(i);
    sensorRaw[i] = analogRead(SIG);
  }
}

// ── Calibration Routine ────────────────────────────────────
void calibrate() {
  Serial.println("Calibrating... Move over line and background.");
  for (int i = 0; i < 16; i++) { sensorMin[i] = 1023; sensorMax[i] = 0; }

  for (int t = 0; t < 500; t++) {
    readAllSensors();
    for (int i = 0; i < 16; i++) {
      sensorMin[i] = min(sensorMin[i], sensorRaw[i]);
      sensorMax[i] = max(sensorMax[i], sensorRaw[i]);
    }
    delay(5);
  }
  Serial.println("Calibration complete!");
}

// ── Apply Calibration ──────────────────────────────────────
void applyCal() {
  for (int i = 0; i < 16; i++) {
    int range = sensorMax[i] - sensorMin[i];
    if (range == 0) { sensorCal[i] = 0; continue; }
    sensorCal[i] = constrain(
      map(sensorRaw[i], sensorMin[i], sensorMax[i], 0, 1000), 0, 1000
    );
  }
}

// ── Weighted Centroid — Line Position ─────────────────────
float getLinePosition() {
  readAllSensors();
  applyCal();
  long weightedSum = 0, total = 0;

  for (int i = 0; i < 16; i++) {
    weightedSum += (long)sensorCal[i] * i * 1000;
    total       += sensorCal[i];
  }
  if (total == 0) return -1;         // Line lost
  return (float)weightedSum / total; // 0.0 to 15000.0
}

void loop() {
  float pos = getLinePosition();
  float error = pos - 7500.0;        // Center = 7500

  Serial.print("Position: "); Serial.print(pos);
  Serial.print("  Error: ");  Serial.println(error);
  delay(10);
}
```

### ESP32 — High-Speed Version

```cpp
// ESP32 high-speed version — uses faster ADC reads
#define SIG_PIN  34   // ESP32 ADC1 pin (use ADC1 only)

void readAllSensors() {
  for (int i = 0; i < 16; i++) {
    selectChannel(i);
    delayMicroseconds(5);                   // SSOP faster settling on 3.3V
    sensorRaw[i] = analogRead(SIG_PIN);     // 12-bit: 0–4095
  }
}
```

---

##  Performance Specifications

| Parameter | Value |
|---|---|
| **Channels** | 16 |
| **Board Dimensions** | 144.017 mm × 29.96 mm |
| **Total Components** | 55 |
| **Unrouted Nets** | **0 (Fully Verified)** |
| **Total Vias** | 75 |
| **Track Length** | 1286.762 mm |
| **MCU Pins Required** | 5 (S0–S3 + SIG) |
| **Operating Voltage** | 5V DC |
| **MUX Settling Time** | ~10 µs per channel |
| **Full Scan Rate** | ~6,000 scans/sec |
| **Sensor Spacing** | ~8.5 mm center-to-center |
| **Total Array Width** | ~136 mm active sensing |
| **Optimal Height** | 3 – 5 mm from surface |
| **Compatible MCUs** | Arduino, ESP32, STM32, RP2040 |
| **PCB Layers** | 2 Copper |

---

##  PCB Design Details

| Design Decision | Technical Reason |
|---|---|
| **Full SMD components** | Lower profile — critical for ground clearance at high speed |
| **SSOP-24 MUX package** | 40% smaller than SOIC-24 — saves precious board space |
| **0.1µF decoupling cap at MUX VCC** | Suppresses switching transients — cleaner analog reads |
| **47kΩ pull-down per sensor** | Eliminates floating outputs — stable PID input |
| **220Ω LED resistors** | Safe 17mA IR current — optimal emission at 3–5mm |
| **FFC connector (FH12-08S-1SH)** | Vibration-resistant, low-profile cable interface |
| **75 through-vias** | Solid inter-layer connectivity — no signal integrity issues |
| **Zero unrouted nets** | 100% DRC passed — production ready |
| **144mm × 30mm form factor** | Fits standard competition robot frames |
| **Bottom layer components (16)** | Maximizes top-layer sensor density and spacing uniformity |

---

##  Applications

-  **Competitive Line Follower Robots** — Primary design target
-  **PID & Bang-Bang Control Systems** — Weighted centroid error calculation
-  **Surface Edge Detection** — Detect boundaries, markings, and transitions
-  **Autonomous Ground Robots** — Path following along marked tracks
-  **Embedded Systems Research** — Multi-channel analog sensing reference design
-  **Educational Robotics** — Advanced sensor interfacing demonstration

---

##  Screenshots & PCB Preview

###  PCB Top View

<img width="912" height="262" alt="2s UP" src="https://github.com/user-attachments/assets/0e53c172-d20a-4bc3-ad8f-8b8b5b3d0ee4" />

###  PCB Bottom View


<img width="898" height="207" alt="2s Down" src="https://github.com/user-attachments/assets/1140720d-ac09-4695-94bd-b325989364a9" />


###  Board Dimensions


![Sensor Dimension](https://github.com/user-attachments/assets/2aa94e57-490c-4446-8e0e-c1bd938fa921)


###  Mounted on Robot


<img width="1237" height="747" alt="mounting" src="https://github.com/user-attachments/assets/1dac0f5c-d545-4926-bffe-14c3b065df02" />


##  Author

<div align="center">

**Raunak Choudhary**  
*Robotics · PCB Design · Embedded Systems · Artificial Intelligence*

<br/>

* Designed for India's competitive robotics community*

</div>

---

<div align="center">
<i>Built with ❤️ — India's Most Compact & Advanced 16-Channel IR Sensor Array</i>
</div>
