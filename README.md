# PoC Exploits Collection

This repository contains proof-of-concept (PoC) exploits and research for various CVEs and vulnerabilities, primarily for educational and security testing purposes. Each folder contains a specific exploit, script, or research artifact related to a particular vulnerability.

## Included Exploits

| Vulnerability Description                        | CVE ID         | PoC Location/Link                                      |
|--------------------------------------------------|----------------|-------------------------------------------------------|
| Ivanti Endpoint Manager XXE                      | CVE-2024-37397 | [CVE 2024-37397](./CVE%202024-37397/)                |
| Ivanti Avalanche XXE                             | CVE-2024-38653 | [CVE 2024-38653](./CVE%202024-38653/)                |
| CrushFTP SSTI                                    | CVE-2024-4040  | [CVE 2024-4040](./CVE%202024-4040/)                  |
| HPE Insights Remote Support XXE                  | CVE-2024-53675 | [CVE 2024-53675](./CVE%202024-53675/)                |
| HPE Insights Remote Support RCE (Theoretical)    | CVE-2024-53676 | [CVE-2024-53676](./CVE-2024-53676/)                  |
| Sante PACS Stack Buffer Overflow (DoS)           | CVE-2025-2263  | [CVE-2025-2263](./CVE-2025-2263/)                    |
| CrushFTP Authentication Bypass                   | CVE-2025-2825  | [CVE-2025-2825](./CVE-2025-2825/)                    |

For details on each exploit, see the respective folder and its README.

### Highlight: CVE-2025-2263
A stack buffer overflow in Sante PACS (version < 4.2.0) that can be triggered by sending a specially crafted encrypted username, leading to denial of service. Full technical details and writeup are available at:

- [PwnFuzz Labs: Sante PACS CVE-2025-2263 Buffer Overflow](https://labs.pwnfuzz.com/posts/sante-pacs-cve-2025-2263-buffer-overflow/)

## Disclaimer
All code and exploits in this repository are provided for educational and authorized security testing purposes only. The authors and contributors do **not** accept any liability for misuse or damage caused by the use of these materials. Use responsibly and only on systems you have explicit permission to test.

## License

The code in this repository is licensed under the [Apache License](LICENSE).
