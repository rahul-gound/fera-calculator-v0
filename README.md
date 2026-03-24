# FERA Calculator v0

A calculator application for computing Foreign Exchange Regulation Act (FERA) related financial values, penalties, and compliance metrics.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Overview

FERA Calculator v0 is an early-stage tool designed to help users calculate and assess financial figures related to the Foreign Exchange Regulation Act (FERA). It provides a straightforward interface for performing common FERA-related computations, such as penalty estimation, compliance checks, and foreign exchange conversions.

> **Note:** This is version 0 (`v0`) — an initial prototype. APIs and features are subject to change.

## Features

- 💱 **Foreign Exchange Conversion** — Compute exchange values between currencies under FERA guidelines.
- ⚖️ **Penalty Estimation** — Estimate potential penalties for FERA violations.
- 📊 **Compliance Metrics** — Evaluate transactions against FERA thresholds and limits.
- 🔢 **Simple Calculator Interface** — Clean and intuitive UI for performing calculations.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/) v16 or higher (if using the web interface)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/rahul-gound/fera-calculator-v0.git
   cd fera-calculator-v0
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Start the development server:**

   ```bash
   npm start
   ```

4. Open your browser and navigate to `http://localhost:3000`.

## Usage

1. Select the type of calculation you want to perform (e.g., penalty, conversion, compliance check).
2. Enter the required values in the input fields.
3. Click **Calculate** to see the result.

Example — estimating a FERA penalty:

```
Transaction Amount : ₹5,00,000
Violation Type     : Unauthorized Foreign Exchange
Penalty Rate       : 3x of violation amount
Estimated Penalty  : ₹15,00,000
```

## Project Structure

```
fera-calculator-v0/
├── public/          # Static assets
├── src/             # Application source code
│   ├── components/  # UI components
│   ├── utils/       # Calculation utilities
│   └── index.js     # Entry point
├── package.json
└── README.md
```

## Contributing

Contributions are welcome! To get started:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit: `git commit -m "Add your feature"`
4. Push to your branch: `git push origin feature/your-feature-name`
5. Open a Pull Request.

Please ensure your code follows the existing style and includes relevant tests.

## License

This project is licensed under the [MIT License](LICENSE).

---

> **Disclaimer:** This tool is intended for informational and educational purposes only. It does not constitute legal or financial advice. Always consult a qualified professional for FERA/FEMA compliance matters.
