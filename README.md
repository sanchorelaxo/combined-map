# Combined Rothschild & Epstein 3D Network Map

This repository contains a merged 3D visualization of two distinct but interconnected networks:
1. **The House of Rothschild** (Generations 1-7, genealogical and financial network)
2. **The Epstein Network** (Intelligence, financial, political, and criminal hubs)

Both entities remain structurally unchanged and are rendered side-by-side in a single Three.js scene, with specific cross-connections highlighting documented or alleged overlaps.

## Viewing the Map

Open `index.html` in a modern web browser. 
- **Left side (X ≈ 0)**: Rothschild family tree and financial network.
- **Right side (X ≈ 300)**: Epstein network hubs (Meyer Lansky, James Angleton, Leslie Wexner, Jeffrey Epstein, Mossad) and their associated clusters.

### Controls
- **Left Click + Drag**: Rotate the 3D view.
- **Right Click + Drag**: Pan the view.
- **Scroll**: Zoom in/out.
- **Click on a Node**: View detailed notes and historical context in the bottom panel.
- **Double Click**: Auto-focus the camera on the selected node.

## Cross-Connections (Magenta Lines)

The following links bridge the two networks, rendered in magenta to distinguish them from internal family/intelligence connections:

1. **Ariane de Rothschild ↔ Jeffrey Epstein**  
   *Note*: Epstein admitted in an email that he represents the Rothschilds.

2. **Nathaniel Philip Rothschild, 5th Baron (Gen 6) ↔ Jared Kushner**  
   *Note*: Documented as very close friends and co-sponsors of the Albanian Sazan Island project.

3. **Mossad ↔ Mayer Amschel Rothschild (Founder)**  
   *Note*: Represents the historical and modern intelligence/financial network overlaps originating from the dynasty's foundation.

4. **Mossad ↔ James Mayer de Rothschild (French Branch)**  
   *Note*: Highlights the French branch's historical intelligence and financial overlaps.

## Visual Legend

- **Colored Spheres (Rothschild)**: Represent generations (Gen 1-5+), color-coded by generation.
- **Green Spheres (Epstein)**: Represent Epstein network hubs and secondary nodes.
- **Gray Lines**: Standard parent-child or organizational connections.
- **Red Lines**: Intermarriages (Rothschild network).
- **Yellow Lines**: Special internal Epstein network connections (e.g., between major hubs).
- **Magenta Lines**: Cross-connections between the Rothschild and Epstein networks.

## Data Sources & Structure

- **Rothschild Data**: Sourced from genealogical records, historical financial documents, and established biographical sources.
- **Epstein Data**: Sourced from investigative journalism, court documents, flight logs, and declassified intelligence records.
- **Architecture**: Both datasets are normalized into a unified `nodes` and `links` format, allowing the Three.js renderer to process them in a single pass while maintaining their distinct spatial clustering.

## Modifications from Original Repos

- Original repositories (`rothschild-map` and `epstein-map`) remain untouched.
- Epstein node coordinates have been offset by `X + 300` to prevent visual overlap.
- Camera defaults to a centered position `(150, 50, 350)` to frame both networks simultaneously.
