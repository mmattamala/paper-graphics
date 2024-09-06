# Paper Graphics

Resources to help you make scientific figures for your robotics papers.

It mainly stores the assets used in a tutorial I prepared in 2023, which is constantly being updated.

> Matias Mattamala (2023), "Designing Graphics for Scientific Publications". [Online (Google Slides)](https://docs.google.com/presentation/d/1J_7wpXovbtMO1EP84cikXDzGpwWb-QxdlihMAiNg3XE/edit?usp=sharing)

The tutorial summarizes the workflow I follow when making figures for my papers and other advice. The goal was on "low budget" solutions, using open-source or other free-to-use software tools instead of expensive professional software.

## Other resources

(This section will be extended in the future)

- **Software tools**
  - [Inkscape](https://inkscape.org/release/inkscape-1.3/gnulinux/ubuntu/ppa/dl/): Wonderful vector graphics software
  - [Google Drawings](https://docs.google.com/drawings/): Easy diagrams from your Google account
  - [draw.io](https://draw.io): Easy to use though more advanced flowchart software
  - [GIMP](https://www.gimp.org/): Brilliant bitmap manipulation software
- **Vector graphics**
  - [Inkscape](https://inkscape.org/release/inkscape-1.3/gnulinux/ubuntu/ppa/dl/): Wonderful vector graphics software
  - [Bezier Game](https://bezier.method.ac): Online game to learn to use the Pen tool in Inkscape (and other vector graphics software)
  - [Map Chart](https://www.mapchart.net/europe.html): To generate colored maps with highlighted countries
- **Colors**
  - Claus O. Wilke (2019), ["Fundamentals of Data Visualization"](https://clauswilke.com/dataviz/index.html)
  - [DaltonLens](https://daltonlens.org/colorblindness-simulator): Color blindness simulator
  - David Nichols, ["Coloring for Colorblindness"](https://davidmathlogic.com/colorblind/)
- **Other tutorials on designing scientific figures**
  - Peter Fankhauser (2018), ["Graphic and Video Editing for Scientific Publications"](https://www.youtube.com/watch?v=MkbPeSmJGI0)
  - Alice Chen Kitterman (2021), ["Designing an effective graphic abstract"](https://www.science.org/doi/10.1126/scirobotics.abn1724)
  - Nataliya Rokhmanova, Andrew K. Schulz (2023), ["Explaining scientific findings through figures in publications, presentations, and posters "](https://github.com/nrokh/ScientificFigures)
- **Presentation tools**
  - [Projecteur](https://github.com/jahnf/Projecteur): To spotlight parts of your screen
    - Installation instructions: [link](https://jahnf.github.io/Projecteur/doc/LinuxRepositories.html)
      - Ubuntu 20.04
      - `curl -1sLf 'https://dl.cloudsmith.io/public/jahnf/projecteur-develop/cfg/gpg/gpg.544E6934C0570750.key' | sudo gpg --dearmor -o /usr/share/keyrings/jahnf-projecteur-develop-archive-keyring.gpg`
      - `curl -1sLf 'https://dl.cloudsmith.io/public/jahnf/projecteur-develop/cfg/setup/config.deb.txt?distro=ubuntu&codename=bionic' > /etc/apt/sources.list.d/jahnf-projecteur-develop.list`
      - `sudo apt update`
      - `sudo apt install projecteur`
      - Add Ubuntu shortcut to: `projecteur -c spot=toggle`
  - [Key-mon](https://github.com/scottkirkwood/key-mon): To show your mouse actions on the screen
  - [ScreenKey](https://www.omgubuntu.co.uk/screenkey-show-key-presses-screen-ubuntu): It shows what keyboard keys you are pressing (full sequence, but not mouse)

## License

All the images in assets are designed or photographed by me, except from:

- [intel_d435i.png](assets/intel_d435i.png), from Intel
- [microstrain_gx5_imu.png](assets/microstrain_gx5_imu.png), from Microstrain
