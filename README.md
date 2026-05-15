# RubiTwist | High-Performance Rubik's Cube Solver

RubiTwist is a full-stack application that solves any 3x3 Rubik's Cube in under 22 moves. It leverages low-level C++ efficiency for the search algorithm and Three.js for real-time 3D visualization.

## Key Features
- **Kociemba's Two-Phase Algorithm:** Computes solutions in sub-millisecond time.
- **State-Space Search:** Uses IDA* and Bitwise operations to manage $4.3 \times 10^{19}$ states.
- **3D Interactive UI:** Built with React Three Fiber for a seamless user experience.
- **Hybrid Architecture:** C++ solving engine integrated with a Node.js/Express backend.

##  Tech Stack
- **Frontend:** React.js, Three.js, Tailwind CSS
- **Backend:** Node.js, Express
- **Engine:** C++ (Compiled to binary)

##  Installation
1. Clone the repo: `git clone https://github.com/your-username/RubiTwist`
2. Compile the solver: `g++ -O3 solver.cpp -o solver`
3. Install NPM packages: `npm install`
4. Start the app: `npm start`
