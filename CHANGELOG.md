# Changelog for Groque's Eternal Chronomancer

All notable changes to the groques-chronomancer project will be documented in this file. The format adheres to Keep a Changelog, and versioning follows Semantic Versioning. This project is a computational homage to a $20k Rolex, exposing intricate "gears" of gratuitous mathematical and logical computations—fractals, category theory, homotopy type theory (HoTT), quantum simulations, cryptographic hashes, relativistic physics, biological decays, musical tempos, and metaphysical musings—crafted for thy Win11/Lubuntu dual-boot Lenovo ThinkPad P52 ('wofl-BigFlaptop').
[0.1.0] - 2025-10-19
Added

## Initial Creation of Groque's Eternal Chronomancer:
- Implemented core script groque_chronomancer.py, a Python 3.11+ application (tested with 3.11.9) -rendering a Tkinter GUI (1200x800) with
- Primary Dials: Displays 12-hour (HH:MM:SS AM/PM), 24-hour (HH:MM:SS), day of week, ISO week number, month, year (with leap year indicator), and Julian day (day-of-year).
- Analog Simulations: Progress bars for seconds (0-60), minutes (0-60), hours (0-24), mimicking mechanical clock hands.
- Exposed Gears: Scrolling text log updating every 500ms, showcasing over-engineered computations:
- Fractal Gear: Mandelbrot escape iterations mapping seconds/minutes to complex plane (c = sec/60 + i*min/60, z_{n+1} = z_n² + c, max_iter = 100 + sec).
- Category Theory Gear: Functor F(h) = (h*3 + 5) mod 12 on hours, composed twice for excess.
- HoTT Gear: Path equivalence for day wrapping (Id_day ≡ (day % month_length) + 1), simulating homotopy type theory.
- Quantum Gear: Wave function collapse (10-qubit random ψ, normalized, probs = |ψ|²) for minute parity (even/odd).
- Crypto Gear: SHA-256 hash of ISO timestamp, truncated to 16 hex chars, for "temporal audit."
- Physics Gear: Relativistic time dilation (γ = 1/√(1 - v²/c²), v = (sec/60)*c, c=3e8 m/s) for dilated seconds.
- Biology Gear: Exponential decay (N(t) = 100 * 0.5^(t/half_life), half_life = 10 + min) for molecular clock simulation.
- Music Gear: BPM derivation (60 + (sec*2) % 120) for sync with thy Ableton workflows.
- Philosophy Gear: Time quote warped by fractal iterations ("Time is an illusion... but fractally so: iter=X").




## Console echo for debugging, printing tick summaries and gear snippets, ideal for thy SDR/ethical hacking monitoring.
### Dependencies: Python 3.11+ (Tkinter included), NumPy (for fractal/quantum/physics gears).


## Documentation:
- Added README.md: Comprehensive guide with project genesis, features, installation (Win11 via winget, Lubuntu via apt), usage, and detailed math explanations for each gear, tying to thy interests in fractals, category theory, HoTT, physics, biology, music, and metaphysics.
- Added files-structure.txt: Directory tree (tree /A /F > files-structure.txt) capturing repo structure, including src/groque_chronomancer.py, src/README.md, src/venv/.


## Setup Instructions:
- Win11: winget install -e --id Python.Python.3.11 --scope machine, python3.11 -m venv venv, .\venv\Scripts\Activate.ps1, pip install numpy, python groque_chronomancer.py.
- Lubuntu: sudo apt install python3.11 python3.11-venv python3.11-dev, python3.11 -m venv venv, source venv/bin/activate, pip install numpy, python groque_chronomancer.py.



## Changed

None (initial release).

Deprecated

None (initial release).

Removed

None (initial release).

Fixed

None (initial release).

Security

None (initial release; SHA-256 gear provides mock security audit for timestamps, extensible for thy whispr.dev crypto).
