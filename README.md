
## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- NPM (comes with Node.js)

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/thedinosoar/godot-iframe-test.git
   cd godot-iframe-test
   ```

2. Navigate to the godot-server directory:
    ```bash
    cd godot-server
    ```

3. Install the dependencies:

    ```bash
    npm install
    ```
    or
    ```bash
    yarn
    ```

4. Copy your exported Godot HTML5 files or directly export them into the public folder of the godot-server directory.
    Ensure the name of the exported html file is `iframe-test.html`

### Running the Development Server

1. Start the Vite development server:

    ```bash
    npm run dev
    ```

    or

    ```bash
    yarn dev
    ```

2. Open your browser and go to http://localhost:5173 (or the port specified in vite.config.ts).