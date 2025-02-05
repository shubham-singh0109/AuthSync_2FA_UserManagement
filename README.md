# Client-Server Automation with Ansible and Two-Factor Authentication (2FA)

## Introduction
This project aims to automate the management of client-server environments using Ansible while enhancing security with Two-Factor Authentication (2FA). The implementation focuses on efficient automation, secure authentication, and scalability, reducing manual interventions and mitigating security risks.

## Scope
- Automating software installations, configurations, and updates.
- Securing servers with authentication mechanisms.
- Mitigating risks of malicious activities.

## Features
- **Automated Deployments**: Uses Ansible playbooks to manage software installation and system configuration.
- **Secure Authentication**: Implements Two-Factor Authentication (2FA) for enhanced security.
- **Scalability**: Supports multi-server environments with minimal manual intervention.
- **Risk Mitigation**: Reduces vulnerabilities by enforcing security best practices.

## Technologies Used
- **Ansible**: For automation of system management tasks.
- **Linux Servers**: Used for deployment and configuration.
- **Two-Factor Authentication (2FA)**: Enhances security of server access.
- **Python & Bash**: For scripting and additional automation.
- **AWS**: For creating the multiple client servers and a master server and managing the logs on cloud.

## Installation & Setup
1. **Install Ansible**:
   ```bash
   sudo apt update && sudo apt install ansible -y
   ```
   or for macOS:
   ```bash
   brew install ansible
   ```
2. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <project-directory>
   ```
3. **Configure Ansible Inventory**:
   Edit the `inventory.ini` file to define your client-server setup.
4. **Run the Ansible Playbook**:
   ```bash
   ansible-playbook -i inventory.ini setup.yml
   ```
5. **Enable Two-Factor Authentication (2FA)**:
   Follow the setup guide in `docs/2FA_setup.md` to configure 2FA for secure authentication.

## Usage
- Modify `playbooks/` to customize automation scripts as per your environment.
- Run security audits using provided Ansible roles.
- Monitor logs for unauthorized access attempts.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## Contact
For any queries, reach out to **Shubham Singh** at https://shubham-singh0109.github.io/
