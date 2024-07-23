README.md content:

# All in One Cloud Security Scanner GUI with Prowler, ScoutSuite, and CloudSploit

This project aims to provide a unified graphical user interface (GUI) for running multiple cloud security scanning tools, including Prowler, ScoutSuite, and CloudSploit. The GUI simplifies the process of configuring and executing these tools, making it easier for users to assess the security posture of their cloud environments.

## Features

- **Prowler Integration**: Prowler is a command-line tool for auditing the security of AWS accounts and resources. This project integrates Prowler and allows users to run security checks on their AWS environment through the GUI.

- **ScoutSuite Integration**: ScoutSuite is a multi-cloud security auditing tool that supports AWS, Azure, and GCP. With this integration, users can perform comprehensive security assessments across multiple cloud platforms from the GUI.

- **CloudSploit Integration**: CloudSploit is an open-source cloud security and compliance scanning tool that supports AWS, Azure, GCP, Oracle Cloud, and other cloud providers. This project incorporates CloudSploit, enabling users to scan their cloud environments for security risks and compliance violations.

- **Unified GUI**: The project provides a user-friendly graphical interface that consolidates the functionality of Prowler, ScoutSuite, and CloudSploit into a single application. Users can easily configure and run scans, view reports, and manage their cloud security assessments from a centralized location.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/all-in-one-cloud-security-scanner.git
```

2. Install the required dependencies:

```bash
cd all-in-one-cloud-security-scanner
pip install -r requirements.txt
```

3. Set up the individual security scanning tools (Prowler, ScoutSuite, CloudSploit) according to their respective documentation.

## Usage

1. Run the main application:

```bash
python src/main.py
```

2. The GUI will launch, allowing you to select the desired security scanning tool (Prowler, ScoutSuite, or CloudSploit).

3. Configure the tool settings and provide the necessary credentials or access information.

4. Initiate the security scan from the GUI.

5. View the scan results and reports within the application.

For detailed instructions on using each security scanning tool, refer to the documentation in the `docs/` directory.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request. Make sure to follow the contribution guidelines outlined in the repository.

## License

This project is licensed under the [MIT License](LICENSE).