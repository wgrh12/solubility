# solubility
This app was created by following the tutorial "How to Build Bioinformatics Tools" at
https://www.youtube.com/watch?v=LHM0Couv0w4&t=500s by youtube dataprofessor Dr. Chanin S. 
The app worked locally at http://localhost:8501 but not remotely. After deployed at heroku.com, it cannot be run due to the inability for pip (pip install -r  requirements.txt) to install rdkit which was only able to be installed by conda install -c rdkit rdkit OR conda install -c conda-forge rdkit. 
