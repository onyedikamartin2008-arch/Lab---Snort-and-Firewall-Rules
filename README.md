# Snort and Firewall Rules Lab

Documentation repository for the Cisco CyberOps **Snort and Firewall Rules** lab.

> **Evidence policy:** This repository contains documentation templates and placeholders. Replace every placeholder with your own terminal output, screenshots, and observations from your lab. Do not claim a step was completed until you have captured the evidence.

## Lab objectives

- Prepare the CyberOps Workstation virtual environment.
- Observe Snort IDS alerts during a simulated malicious-file download.
- Capture the network transaction with `tcpdump`.
- Inspect and modify `iptables` firewall rules.
- Verify that the firewall blocks traffic to the offending server.
- Terminate and clean up the Mininet environment.

The source lab organizes these objectives into Part 1, Part 2, and Part 3. See `docs/LAB_GUIDE.md` for the documentation workflow.

## Repository structure

```text
.
├── README.md
├── COMMANDS.md
├── EVIDENCE_CHECKLIST.md
├── .gitignore
├── LICENSE
├── docs/
│   ├── LAB_GUIDE.md
│   ├── OBSERVATIONS.md
│   └── TROUBLESHOOTING.md
├── commands/
│   └── lab-commands.sh
├── scripts/
│   └── README.md
├── screenshots/
│   ├── 01-environment/
│   ├── 02-snort-ids/
│   ├── 03-pcap/
│   ├── 04-iptables/
│   └── 05-cleanup/
└── evidence/
    └── README.md
```

## Lab environment

Fill this in after completing the lab:

| Item | Value |
|---|---|
| Host OS | TODO |
| Virtualization | Oracle VirtualBox |
| VM | CyberOps Workstation |
| VM network mode | TODO |
| Lab date | TODO |
| Student | TODO |
| Mininet topology | `cyberops_extended_topo_no_fw.py` |
| IDS | Snort |
| Firewall | iptables |

## Key evidence

Document your own results for:

1. CyberOps VM network configuration and connectivity.
2. R1 shell identity and Snort startup.
3. H5 → H10 download attempt.
4. Snort alert details.
5. `nimda.download.pcap` creation and size.
6. Existing iptables chains.
7. FORWARD/DROP rule insertion.
8. Failed download after firewall blocking.
9. Mininet termination and cleanup.

## Safety / scope

This is a controlled lab environment. Perform the traffic generation only inside the provided CyberOps/Mininet lab and do not use the simulated malware-server workflow against systems you do not own or have permission to test.

## Status

- [ ] Part 1 completed
- [ ] Part 2 Step 1 completed
- [ ] Part 2 Step 2 completed
- [ ] Part 3 completed
- [ ] Screenshots reviewed
- [ ] Evidence checklist completed
- [ ] Git repository pushed
