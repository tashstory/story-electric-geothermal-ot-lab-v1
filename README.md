# story-electric-geothermal-ot-lab-v1
An interactive 3D geothermal power plant for learning how OT and IT run, connect and are secured. Walk the plant, operate the plant via the HMI, trace packets, edit firewall rules, follow Kerberos and MFA, hunt in SOC logs, and see NERC CIP mapped to real controls. Turn off safeties and blow up the plant! Try and give the neighborhood power! Vibe coded with claude and runs in your browser.

Note: This is not meant to be a comprehensive simulation but a learning tool for the basics! Feel free to reach out if you'd like any additions and modify it yourself till your hearts content!

# ⚡ Story Electric · Geothermal OT/IT Security Lab

**[▶ Launch the lab](https://YOUR-USERNAME.github.io/YOUR-REPO/)** — no install, no login. Works best in a desktop browser (Chrome, Edge, Firefox, Safari); touch controls on phones and tablets.

Story Electric is a fictional geothermal power plant you can walk through, run and break, to learn how
operational technology (OT) and IT work together, and how they're secured.

### What you can do
- 🏭 **Walk the plant** in first person: control building stacked by Purdue level, turbine hall, wellfield, cooling yard, switchyard and a town on the grid
- 🖥️ **Operate the HMI** and watch the plant respond: dispatch, trips, protection systems, and what happens when they're bypassed
- 📦 **Trace packets** hop by hop, and X-ray real protocol fields (Modbus, DNP3, IEC 61850, Kerberos, TLS…)
- 🧱 **Edit live firewall rules** and see what an attacker could reach from any compromised device
- 🔐 **Follow authentication** across separate IT and OT Active Directory forests, the VPN, MFA and the jump host
- 🔍 **Hunt in SOC logs** with an XQL-style query console
- 🗂️ **Run OT security operations:** asset inventory, vulnerability triage, patching, change management, USB media control, red-vs-blue replay and an incident response drill
- 📜 **See NERC CIP mapped to the lab**, with a live audit-readiness score
- ⏱️ **Shift mode:** run the plant through a full shift, follow grid demand and catch faults early on the trends via PI data monitoring!

---

## ⚠️ Disclaimer

**Educational use only.** This project is a learning tool. It is not a real control system, product,
training certification, or authoritative reference.

- **Fictional.** Story Electric, its people, accounts, IP addresses, network design and data are invented.
  Any resemblance to a real organization or system is coincidental. Real-world incidents are referenced
  only as publicly reported history.
- **Simplified.** Plant physics, protocols, timings and security controls are simplified for teaching and
  may not match any specific vendor, product or site. Don't use it to design, operate or assess a real system.
- **Not compliance, legal or engineering advice.** NERC CIP, IEC 62443 and other standards are summarized
  in plain language and may be incomplete or out of date. Applicability and requirements depend on your
  organization; always consult the current official standards and your compliance, legal and engineering teams.
- **Defensive focus.** Attack scenarios show *why* controls exist and how defenders detect and respond.
  The lab contains no working exploit code and performs no real network activity. Only test systems you
  own or are explicitly authorized to test.
- **No data collected.** The lab runs entirely in your browser. Progress is saved only in your own
  browser's local storage. Nothing is sent to a server.
- **Provided as-is,** without warranty of any kind. 

Not affiliated with, endorsed by, or representing NERC, ISA/IEC, any utility, or any vendor/company.

---

### Feedback
Found a bug or an inaccuracy, or have an idea? [Open an issue](../../issues). Corrections from OT and grid
practitioners are especially welcome.
