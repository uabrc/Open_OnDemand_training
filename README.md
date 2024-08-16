# Open_OnDemand_training

Hands-on training material for getting started with Open OnDemand on Cheaha, including practical examples

=============================================

- Clone the repository to your local machine
- To run/view the slides format and contents:
  - just open the `index.html` file directly in your browser.
- To update/contribute contents, formats, etc:
  - You can open the cloned repository in your terminal.
    - Navigate to the **ood_training** folder.
    - Run the command `npm start`.
  - or with VSCode (especially useful if you prefer to edit or add content), then run the command `npm start`
- If you do not have `npm` installed on your computer, you need to install `Node.js` and `npm` by running `conda install -c conda-forge nodejs` or using one of the following methods:
  - **macOS**
    - Install Node.js and npm using Homebrew: `brew install node`
  - **Linux**
  
```bash
sudo apt update
sudo apt install nodejs npm
```

- **Project Structure**
  - **index.html**: The main HTML file. Each slide is linked to this main page. It can be run directly as a static HTML file or using npm start.
  - **slides folder**: Contains HTML files for slides.
  - **dist folder**: Contains compiled CSS and JS files.
  - **plugins folder**: Contains various plugins used in the project.

To export your slides as a PDF:

- Open your presentation in a web browser.
- Add `?print-pdf` to the end of the browser's address bar. For example, `http://localhost:1948/slide/ood.html` becomes `http://localhost:1948/slide/ood.html?print-pdf`.
- Press `Ctrl+P` (Windows) or `Cmd+P` (Mac) to print the presentation as a `PDF`.