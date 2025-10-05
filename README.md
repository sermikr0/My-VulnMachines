# My-VulnMachines

A collection of 50+ custom vulnerable machines built with 2025-era flaws.  
Each machine is compact, reproducible, and easy for you to deploy and test.

---

## Highlights

- 50+ machines focused on modern 2025 vulnerabilities.  
- Clear, step-by-step notes per machine.  
- Simple setup options for local or cloud use.  
- Ideal for learning exploitation, post-exploitation, and blue team practice.  

---

## Advanced Machines (selected)

- **AuthMe** — https://www.notion.so/AuthMe-1b4c4193ecb080ae8560ef853fa7b863  
- **WireShid** — https://www.notion.so/WireShid-1b5c4193ecb0805185e6df7a12d053c1  
- **FireJens** — https://www.notion.so/FireJens-1b6c4193ecb080a7b36bd651677ed380  
- **WinWar** — https://www.notion.so/WinWar-1b9c4193ecb0804780bee64cd3111ce8  
- **EasyHot** — https://www.notion.so/EasyHot-1b9c4193ecb08000a376d395303315f3  
- **EcoHack** — https://www.notion.so/EcoHack-1c2c4193ecb080a6bf25c5fe3a882180  
- **Nightwalker** — https://www.notion.so/Nightwalker-1c3c4193ecb080d9996be847809c2fd4  
- **Zerosti** — https://www.notion.so/Zerosti-1d0c4193ecb080c6be51c81f6cc3a9e4

Each link goes to the full write-up and setup instructions.

---

## CTFs & write-ups

- **40 CTFs** collection and write-ups.  
  https://www.notion.so/40-CTF-1f1c4193ecb080deaf48c3828a9e368e

---

## Quick start (how you, the user, deploy a machine)

1. Clone this repo.  
   `git clone git@github.com:sermikr0/My-VulnMachines.git`

2. Open the machine folder or the Notion write-up.  
   Read the setup steps provided for that machine.

3. Choose a deployment method (one of these common options):  
   - Run with `docker-compose up` if a compose file exists.  
   - Import the VM into VirtualBox/VMware when an OVA is provided.  
   - Use Vagrant with `vagrant up` if Vagrantfile is included.

4. Start the machine and follow the enumeration steps in the write-up.  
   The notes list exact commands and expected outputs.

5. Reset or destroy the VM when finished.  
   Use the provider commands shown in the write-up.

---

## Design goals

- Reproducible machines.  
- Minimal prerequisites for you to run.  
- Clear, step-by-step exploitation paths.  
- Practical tasks that mirror real 2025 attack surfaces.

---

## Notes on scope

- These machines are lab exercises only.  
- They are separate from any certification material.  
  (Not linked to certificates or official exams.)

---

## Contribute or run your own

- Want a new machine?  
  Add a folder with VM image or container, and a Notion-style write-up.  
- Follow the existing folder structure and naming convention.  
- Provide a short `README.md` per machine with required commands.

---

## Contact

- Telegram: https://t.me/saidakbarxon_m  
- LinkedIn: https://www.linkedin.com/in/saidakbarxon-maxsudxonov-555609279/  
- GitHub: https://github.com/sermikr0

---

If you want, I will:
- Convert each Notion link into a local `README.md` entry.  
- Add one-click `docker-compose` or `Vagrantfile` examples per machine.  
- Produce a printable cheat-sheet for quick enumeration steps.
