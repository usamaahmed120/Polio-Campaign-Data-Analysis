# Polio Campaign Data Analysis

This repository contains a Python script for analyzing and validating data from Polio Campaigns. The script automates the process, making it more efficient and accurate. It utilizes the Pandas and OS libraries for data processing and file management.

## Features

- Analyzes the Form2A file, which summarizes daily activities by Area Supervisors during the campaign.
- Validates the Form2A data according to company instructions and identifies discrepancies.
- Matches the Form2A information with the LineList, ZeroDose, and AFP files to ensure the correct number of entries.
- Provides detailed information on Still Missed Children (SMC), ZeroDose, and Acute Flaccid Paralysis (AFP) cases.
- Improves data analysis efficiency and reduces manual errors.

## Usage

1. Make sure you have Python and the required dependencies (Pandas, OS) installed.
2. Rename the Form2A file to `Form2A.csv` and place it in the `input` directory.
3. Optionally, rename the LineList, ZeroDose, and AFP files to `LineList.csv`, `ZeroDose.csv`, and `AFP.csv`, respectively, and place them in the `input` directory as well.
4. Run the script without making any changes to the code.
5. The script will automatically process the files in the `input` directory.
6. The resulting analysis and validation reports will be stored in the `output` directory.

## Directory Structure

- `input`: Contains the input files (Form2A, LineList, ZeroDose, AFP).
- `output`: Stores the analysis and validation reports generated by the script.

## Contributions

Contributions to this project are welcome. If you would like to enhance the script or add new features, please feel free to submit a pull request. Kindly ensure that the changes align with the project's goals and maintain code quality.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute the code for both commercial and non-commercial purposes.

## Acknowledgements

We would like to thank the Data Support Center (DSC) for providing the inspiration and guidance to develop this script. It significantly improves the efficiency and accuracy of Polio Campaign data analysis, streamlining the process for better insights and decision-making.
