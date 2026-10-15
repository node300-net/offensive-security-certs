# 🪪 Zertifikats-Steckbriefe

[← zurück zur Übersicht](../README.md) · Recherchestand **15. Oktober 2026** · Marker: ✅ Primärquelle · 🟦 unabhängige Quelle · ⚠️ unverifiziert/Schätzung · ❌ trifft nicht zu

> [!NOTE]
> **Lernaufwand = Community-Schätzung.** Wir zitieren (a) **Inhaltsstunden des Anbieters** (✅, aber Marketing – meist ohne Übungszeit), (b) den Aggregator **[PWN PATH](https://thepwnpath.win/which-cert-should-i-take/)** 🟦 (Methodik nicht offengelegt) und (c) **Einzel-Erfahrungsberichte** 🟦 wie [time0ut – „Ctrl+Alt+Certified“](https://www.time0ut.com/posts/blogs/ctrl_alt_certified.html) (eine Person, die die Zertifikate *nacheinander* machte – spätere Werte profitieren vom Vorwissen). **Schwierigkeit** (🌶️ 1–5) ist ⚠️ **unsere Einschätzung**.

## 📚 Inhalt

| Anbieter | Zertifikate |
|---|---|
| 🐉 OffSec | [OSCP+](#-oscp--oscp-pen-200) · [OSEP](#-osep-pen-300) · [OSWE](#-oswe-web-300) · [OSED](#-osed-exp-301) · [OSEE](#-osee-exp-401) · [OSCE³](#-osce³) · [OSWA](#-oswa-web-200) · [OSDA](#-osda-soc-200) · [OSTH](#-osth-th-200) · [OSIR](#-osir-ir-200) |
| 📦 Hack The Box | [CPTS](#-htb-cpts) · [CWES (ex CBBH)](#-htb-cwes-ex-cbbh) · [CDSA](#-htb-cdsa) · [CWEE](#-htb-cwee) · [CAPE](#-htb-cape) · [CJCA](#-htb-cjca) |
| 🧑‍🏫 TCM Security | [PJPT](#-pjpt) · [PNPT](#-pnpt) |
| 🎓 INE | [eJPT](#-ejpt) · [eCPPT](#-ecppt) · [eWPT](#-ewpt) |
| 🏰 Altered Security | [CRTP](#-crtp) · [CRTE](#-crte) (CRTM/CARTP/CARTE → [Hidden Gems](hidden-gems.md)) |
| 🎯 Zero-Point Security | [CRTO](#-crto) · [CRTL](#-crtl-ex-crto-ii) |
| 🏛️ GIAC / SANS | [GPEN](#-gpen) · [GXPN](#-gxpn) · [GWAPT](#-gwapt) · [GCIH](#-gcih) (GCPN → [Hidden Gems](hidden-gems.md#-gcpn-giac-cloud-penetration-tester)) |
| 🧾 CompTIA | [Security+](#-comptia-security) · [PenTest+](#-comptia-pentest) |
| 🎩 EC-Council | [CEH & CEH Practical](#-ceh--ceh-practical) |
| 🌐 PortSwigger | [BSCP](#-bscp-burp-suite-certified-practitioner) |
| 🇬🇧 CREST | [CPSA → CRT → CCT INF / CCT APP](#-crest-cpsa--crt--cct-inf--cct-app) |

---

## 🐉 OffSec

> **Gemeinsames Preismodell (✅ [offsec.com/pricing](https://www.offsec.com/pricing/)):** *Course + Cert Bundle* **1'749 USD** (90 Tage Lab, 1 Prüfungsversuch) · *Learn One* **2'749 USD/Jahr** (365 Tage, 2 Versuche, Proving Grounds Practice, PEN-103/KLCP, PEN-210/OSWP inklusive) · Rabatte: **Aspire** 10/15/20 % für Inhaber von 1/2/3+ OffSec-Zertifikaten, **Achieve** bis 10 % für Vollzeit-Studierende. *Learn Unlimited* wurde per **01.01.2026 eingestellt** ✅ ([OffSec Help](https://help.offsec.com/hc/en-us/articles/43304493537940-Sunsetting-Learn-Unlimited-and-Moving-Forward-with-Learn-Enterprise)).
>
> **Ablaufende vs. lebenslange Zertifikate (✅ [AMF FAQ](https://help.offsec.com/hc/en-us/articles/47648267491476-OffSec-Annual-Maintenance-Fee-AMF-FAQ)):** Nach 3 Jahren laufen ab: **OSCP+, OSAI+, OSCC-SEC, OSCC-SJD, OSTH, OSIR** – sie brauchen **jedes Jahr** Maintenance (AMF **145 USD/Jahr** oder AMP). **Lebenslang:** OSCP, OSAI, OSWP, OSWA, OSWE, OSEP, OSED, OSEE, OSDA, KLCP, OSCE³.

### 🐉 OSCP / OSCP+ (PEN-200)

| | |
|---|---|
| 🧪 **Format** | 🛠️ Hands-on, **proctored**: 3 Standalone-Maschinen (je 10 Initial Access + 10 PrivEsc) + **1 AD-Set** mit 3 Maschinen (40 Punkte, „assumed breach“) ✅ [Exam Guide](https://help.offsec.com/hc/en-us/articles/360040165632-OSCP-Exam-Guide) |
| ⏱️ **Prüfung** | **23 h 45 min** + **24 h** für den Report (PDF in .7z) ✅ |
| 🎯 **Bestehen** | 70/100 Punkte – **bis 30.11.2026**; ab **01.12.2026** „equated scaled scoring“ pro Prüfungsset 🟦 ([OffSec Blog laut Index](https://www.offsec.com/blog/oscp-scoring-update/) – Abruf 15.10.2026 von hier 404; bestätigt über Suchindex) · Format unverändert ✅ [Exam Guide](https://help.offsec.com/hc/en-us/articles/360040165632-OSCP-Exam-Guide) |
| 🎓 **Voraussetzungen** | Formal keine; empfohlen: TCP/IP, Windows-/Linux-Administration, Bash/Python ✅ [PEN-200](https://www.offsec.com/courses/pen-200/) |
| 💰 **Preis** | Bundle **1'749 USD** · Learn One **2'749 USD** · **Standalone-Prüfung 1'699 USD** ✅ · CH: Digicomp-Kurs (5.5 Tage + Learn One) **CHF 6'500** zzgl. MWST ✅ [Digicomp](https://digicomp.ch/weiterbildung-cyber-security/offense-testing/offsec-zertifizierungen/kurs-penetration-testing-mit-kali-linux-pen-200-oscp-zertifizierung) |
| 🔄 **Gültigkeit** | **OSCP lebenslang**, **OSCP+ 3 Jahre**: Recertification-Prüfung, qualifizierende OffSec-Prüfung (OSEP/OSWA/OSED/OSEE) oder CPE-Programm (120 CPE) ✅ [PEN-200 FAQ](https://www.offsec.com/courses/pen-200/) **+ jährlich AMF 145 USD** oder AMP ✅ [AMF FAQ](https://help.offsec.com/hc/en-us/articles/47648267491476-OffSec-Annual-Maintenance-Fee-AMF-FAQ) |
| ⏳ **Lernaufwand** | Anbieter: „**321 h of content**“ ✅ · PWN PATH: **~365 h** 🟦 · Erfahrungsbericht: **318 h in 96 Tagen** 🟦 [time0ut](https://www.time0ut.com/posts/blogs/ctrl_alt_certified.html) · Reddit-Median **~4.5 Monate** (10 Berichte) 🟦 [certworthit](https://www.certworthit.com/certificates/oscp/) |
| 🌶️ **Schwierigkeit** | 🌶️🌶️🌶️ – technisch nicht extrem, aber **Zeitdruck + Proctoring + Stress** ⚠️ |
| 🏢 **Anerkennung** | In CH-Pentest-Inseraten häufig „von Vorteil“ (Oneconsult, InfoGuard, RUAG, Deloitte) 🟦 → [Swiss Context](swiss-context.md#-arbeitsmarkt-schweiz). **Nicht** in der DoD-8140-Rolle-541-Liste unserer Quelle 🟦 [Matrix-Auszug](https://www.immunitysec.com/certifications/dod-8140/541/) |
| 🧭 **Lernstrategie** | 1) PEN-200-Module + **alle** Challenge Labs (3 davon „exam-like“ ✅) · 2) Proving Grounds Practice + HTB-Boxen nach Community-Listen · 3) **AD-Set üben** – entscheidet laut Community oft über Bestehen 🟦 · 4) Report-Template *vor* der Prüfung fertig · 5) Prüfungsablauf mit 2–3 Pausen planen |

### 🐉 OSEP (PEN-300)

| | |
|---|---|
| 🧪 **Format** | 🛠️ Hands-on, proctored: Umgehung von AV/AppLocker, Process Injection, AD-Lateral-Movement, Client-Side-Angriffe ✅ [PEN-300](https://www.offsec.com/courses/pen-300/) |
| ⏱️ **Prüfung** | **48 h** (effektiv 47 h 45 min) + **24 h** Report ✅/🟦 [OSEP Exam Guide](https://help.offsec.com/hc/en-us/articles/360050293792-OSEP-Exam-Guide) |
| 🎓 **Voraussetzungen** | Formal keine; OSCP-Niveau erwartet 🟦 [PWN PATH FAQ](https://thepwnpath.win/which-cert-should-i-take/) |
| 💰 **Preis** | 1'749 / 2'749 USD ✅ |
| 🔄 **Gültigkeit** | **Läuft nicht ab** ✅ [PEN-300](https://www.offsec.com/courses/pen-300/) |
| ⏳ **Lernaufwand** | Anbieter: „671 h of content“ ✅ (⚠️ unrealistisch hoch wirkend – vermutlich inkl. aller Labs) · PWN PATH: **~234 h** 🟦 · Review: Kursmaterial in ~2 Monaten 🟦 [cinzinga](https://cinzinga.com/OSEP-PEN-300-Review/) |
| 🌶️ **Schwierigkeit** | 🌶️🌶️🌶️🌶️ ⚠️ |
| 🏢 **Anerkennung** | Standard-Folgezertifikat für Red-Team-/interne Pentest-Rollen; Teil von OSCE³ ✅ |
| 🧭 **Lernstrategie** | C#/PowerShell-Grundlagen vorher; eigene Loader im Homelab gegen Defender testen ([Homelab](homelab-practice.md)); Challenge Labs komplett; Notizen als „Playbook“ pro Technik |

### 🐉 OSWE (WEB-300)

| | |
|---|---|
| 🧪 **Format** | 🛠️ **White-Box**: Quellcode-Review, Auth-Bypass bis RCE, **automatisiertes Exploit-Skript** ✅ [WEB-300](https://www.offsec.com/courses/web-300/) |
| ⏱️ **Prüfung** | 48 h proctored (47 h 45 min) + 24 h Report 🟦 [PWN PATH](https://thepwnpath.win/which-cert-should-i-take/) |
| 🎓 **Voraussetzungen** | Programmierkenntnisse (Python + Lesen von Java/C#/PHP/JS) – ⚠️ unsere Empfehlung |
| 💰 **Preis** | 1'749 / 2'749 USD ✅ · CH: Digicomp-Paket CHF 6'500 ✅ [Digicomp](https://digicomp.ch/weiterbildung-cyber-security/offense-testing/offsec-zertifizierungen/kurs-penetration-testing-mit-kali-linux-pen-200-oscp-zertifizierung) (Verweis „Weiterführende Kurse“) |
| 🔄 **Gültigkeit** | **Läuft nicht ab** ✅ |
| ⏳ **Lernaufwand** | Anbieter: „105 h of content“ ✅ · PWN PATH: **~264 h** 🟦 |
| 🌶️ **Schwierigkeit** | 🌶️🌶️🌶️🌶️ ⚠️ |
| 🏢 **Anerkennung** | Hoch angesehen für AppSec/Code-Review; Teil von OSCE³ ✅ |
| 🧭 **Lernstrategie** | Vorher BSCP/PortSwigger-Labs; Debugger/Remote-Debugging in VS Code üben; jede Kurs-App komplett in ein Python-PoC verwandeln |

### 🐉 OSED (EXP-301)

| | |
|---|---|
| 🧪 **Format** | 🛠️ Windows-User-Mode-Exploit-Dev: Stack Overflows, SEH, DEP/ASLR-Bypass mit ROP, Custom Shellcode, Reverse Engineering ✅ [EXP-301](https://www.offsec.com/courses/exp-301/) |
| ⏱️ **Prüfung** | 48 h proctored + 24 h Report (PDF + Python-PoCs) 🟦 [OSED Exam FAQ](https://help.offsec.com/hc/en-us/articles/360053660531-OSED-Exam-FAQ) |
| 🎓 **Voraussetzungen** | „Ability to read and understand **32-bit Assembly** code at a basic level“ ✅ |
| 💰 **Preis** | 1'749 / 2'749 USD ✅ |
| 🔄 **Gültigkeit** | **Läuft nicht ab** ✅ |
| ⏳ **Lernaufwand** | Anbieter: „932 h of content“ ✅ (⚠️ wirkt marketing-inflationiert) · PWN PATH: **~192 h** 🟦 |
| 🌶️ **Schwierigkeit** | 🌶️🌶️🌶️🌶️ ⚠️ |
| 🏢 **Anerkennung** | Nische, aber Pflichtbaustein für OSCE³ und Sprungbrett zu OSEE ✅ |
| 🧭 **Lernstrategie** | WinDbg täglich; Assembler-Grundlagen (x86) vorab; eigene Mini-Exploits gegen absichtlich verwundbare Programme im isolierten VLAN |

### 🐉 OSEE (EXP-401)

| | |
|---|---|
| 🧪 **Format** | 🛠️ Fortgeschrittene Windows-Exploitation (Mitigation-Bypass, Heap, **64-Bit-Kernel**) ✅ [EXP-401](https://www.offsec.com/courses/exp-401/) |
| ⏱️ **Prüfung** | **72 h** proctored + detaillierter Report ✅ |
| 🎓 **Voraussetzungen** | Empfohlen: 300er-Zertifikate zuerst ✅ [CODE BLUE](https://codeblue.jp/en/program/trainings/offsec-osee/) |
| 💰 **Preis** | **Nur Präsenz-Training** ✅ [EXP-401 FAQ](https://help.offsec.com/hc/en-us/articles/25190559024276-EXP-401-FAQ). Beispiele 2026: Tokio (11.–15.11.2026) **1'760'000 JPY inkl. Steuer** ≈ 9'250 CHF ✅ [CODE BLUE](https://codeblue.jp/en/program/trainings/offsec-osee/); Singapur (Mai 2026) Listenpreis **18'625 SGD** exkl. GST ≈ 12'100 CHF ✅ [Ensign](https://www.ensigninfosecurity.com/courses_and_bootcamps); Black Hat USA (Aug. 2026) – Preis nicht ausgewiesen ⚠️ |
| 🔄 **Gültigkeit** | **Läuft nicht ab** ✅ |
| ⏳ **Lernaufwand** | PWN PATH: ~232 h 🟦 – ⚠️ realistisch zusätzlich Jahre an Vorerfahrung |
| 🌶️ **Schwierigkeit** | 🌶️🌶️🌶️🌶️🌶️ ⚠️ |
| 🏢 **Anerkennung** | Elite-Nische (Exploit-Entwicklung/Vulnerability Research) |
| 🧭 **Lernstrategie** | Erst OSED + Kernel-Grundlagen; Kursabende einplanen (OffSec: Lektüre „each evening“ ✅); nur mit Arbeitgeber-Budget realistisch |

### 🐉 OSCE³

| | |
|---|---|
| 🧪 **Format** | **Kein eigenes Examen** – wird automatisch verliehen nach **OSEP + OSWE + OSED** 🟦 [OSCE³ FAQ](https://help.offsec.com/hc/en-us/articles/4403282452628-OSCE-FAQ) · ✅ [OSCE³-Seite](https://www.offsec.com/certificates/osce3/) |
| 💰 **Preis** | ⚠️ Ableitung: 3 × 1'749 USD = **≥ 5'247 USD** (Bundle) bzw. 3 × 2'749 USD (Learn One) – mit Aspire-Rabatt etwas weniger |
| 🔄 **Gültigkeit** | **Läuft nicht ab** ✅ [AMF FAQ](https://help.offsec.com/hc/en-us/articles/47648267491476-OffSec-Annual-Maintenance-Fee-AMF-FAQ) |
| ⏳ **Lernaufwand** | Summe der drei (PWN PATH ≈ 234 + 264 + 192 ≈ **690 h**) 🟦 ⚠️ Ableitung · Erfahrungsbericht „Zero to OSCE3“ in einem Jahr 🟦 [Jael Koh](https://infosec.jaelkoh.com/2024/my-first-year-in-infosec-zero-to-osce3) |
| 🧭 **Lernstrategie** | Reihenfolge nach Interesse; Aspire-Rabatt steigt mit jedem Zertifikat (10 → 15 → 20 %) ✅ |

### 🐉 OSWA (WEB-200)

| | |
|---|---|
| 🧪 **Format** | 🛠️ **Black-Box-Web** (XSS, SQLi, SSTI, SSRF, XXE, Command Injection …), proctored ✅ [WEB-200](https://www.offsec.com/courses/web-200/) |
| ⏱️ **Prüfung** | **24 h** ✅ + Report |
| 💰 **Preis** | 1'749 / 2'749 USD ✅ |
| 🔄 **Gültigkeit** | **Läuft nicht ab** ✅ |
| ⏳ **Lernaufwand** | Anbieter „231 h of content“ ✅ · PWN PATH **~89 h** 🟦 |
| 🌶️ **Schwierigkeit** | 🌶️🌶️🌶️ ⚠️ |
| 🧭 **Lernstrategie** | Preislich ein schwieriger Fall: BSCP (99 USD) oder HTB CWES (210 USD) decken ähnliche Themen günstiger ab ⚠️ – OSWA lohnt v. a. im Learn-One-Jahr oder als OSCP+-Erneuerung |

### 🐉 OSDA (SOC-200)

| | |
|---|---|
| 🧪 **Format** | 🛠️ **Blue Team**: Angriffe in SIEM-Daten erkennen, 10 Phasen ✅ [SOC-200](https://www.offsec.com/courses/soc-200/) |
| ⏱️ **Prüfung** | **24 h** proctored ✅ |
| 💰 **Preis** | 1'749 / 2'749 USD ✅ |
| 🔄 **Gültigkeit** | **Läuft nicht ab** ✅ |
| ⏳ **Lernaufwand** | Anbieter „374 h of content“ ✅ · PWN PATH ~117 h 🟦 |
| 🧭 **Lernstrategie** | Als „Gegenperspektive“ zum Offensive-Pfad sehr wertvoll; passt zur breiten Fachausweis-Ausbildung ([Swiss Context](swiss-context.md)) |

### 🐉 OSTH (TH-200)

| | |
|---|---|
| 🧪 **Format** | 🛠️ Threat Hunting ✅ [TH-200](https://www.offsec.com/courses/th-200/) |
| ⏱️ **Prüfung** | **8 h** proctored + Report ✅ |
| 💰 **Preis** | 1'749 / 2'749 USD ✅ |
| 🔄 **Gültigkeit** | **3 Jahre** + AMF ✅ |
| ⏳ **Lernaufwand** | Anbieter „54 h of content“ ✅ · ⚠️ keine belastbare Community-Zahl gefunden |

### 🐉 OSIR (IR-200)

| | |
|---|---|
| 🧪 **Format** | 🛠️ Incident Response (u. a. Splunk, Disk-Forensik 🟦 [PWN PATH](https://thepwnpath.win/which-cert-should-i-take/)) ✅ [IR-200](https://www.offsec.com/courses/ir-200/) |
| ⏱️ **Prüfung** | **8 h** proctored ✅ |
| 💰 **Preis** | 1'749 / 2'749 USD ✅ |
| 🔄 **Gültigkeit** | **3 Jahre** + AMF ✅ |
| ⏳ **Lernaufwand** | Anbieter „34 h of content“ ✅ · PWN PATH ~112 h 🟦 |

---

## 📦 Hack The Box

> **Gemeinsames Preismodell seit 12.10.2026 (✅ [HTB Blog](https://www.hackthebox.com/blog/new-academy-pricing)):** Student **10 USD/Monat** (9 €) · Silver Monthly **30 USD** (26 €) · Gold Monthly 95 USD · Platinum 125 USD · **Silver Annual 550 USD/Jahr (469 €)** inkl. **2 Vouchern** (CJCA + 1 Specialist: CPTS/CWES/CDSA) · **Gold Annual 1'400 USD (1'195 €)** inkl. CJCA + 1 Expert-Voucher. **Einzel-Voucher** ✅ [HTB Help](https://help.hackthebox.com/en/articles/13677074-academy-subscriptions): CJCA 105 · CPTS/CWES/CDSA/COAE 210 · CWEE/CAPE/CWPE 350 · CDEP 450 USD. Voucher verfallen **1 Jahr** nach Kauf ✅ [Voucher-Tausch](https://help.hackthebox.com/en/articles/12741804-swapping-exam-voucher) und enthalten laut Drittquelle **2 Versuche** (2. nur mit eingereichtem Report) 🟦 [immunitysec](https://www.immunitysec.com/certifications/htb-cpts/). HTB-Zertifikate **laufen nicht ab** 🟦 (ebd.).

### 📦 HTB CPTS

| | |
|---|---|
| 🧪 **Format** | 🛠️ Black-Box-Pentest eines Unternehmensnetzes, Flags + **kommerzieller Report** ✅ [HTB Certs](https://academy.hackthebox.com/preview/certifications) |
| ⏱️ **Prüfung** | **10 Tage** inkl. Report; verbreitet: 12 von 14 Flags (85 Punkte) + bestandener Report 🟦 [prooftxt](https://prooftxt.com/certifications/cpts/) |
| 🎓 **Voraussetzungen** | Job-Role-Path „Penetration Tester“ (**28 Module**) abschliessen ✅ |
| 💰 **Preis** | Voucher **210 USD** oder Silver Annual **550 USD** inkl. Voucher ✅ |
| 🔄 **Gültigkeit** | Läuft nicht ab 🟦 |
| ⏳ **Lernaufwand** | HTB-Schätzung ≈ 43 „Tage“ à 8 h ≈ **344 h** (zitiert) · Erfahrungsbericht **259 h** 🟦 [BRM](https://www.brunorochamoura.com/posts/road-to-cpts/) · PWN PATH **~391 h** 🟦 |
| 🌶️ **Schwierigkeit** | 🌶️🌶️🌶️🌶️ – Community hält CPTS oft für **schwerer als OSCP+** 🟦 [prooftxt](https://prooftxt.com/certifications/cpts/) |
| 🏢 **Anerkennung** | Wachsend; in HR-Filtern noch seltener als OSCP ⚠️ |
| 🧭 **Lernstrategie** | Jedes Modul mit eigenen Notizen (Obsidian); „Skills Assessments“ ohne Lösung wiederholen; vor der Prüfung 1–2 Wochen Report-Training (z. B. mit SysReptor 🟦 [SysReptor](https://docs.sysreptor.com/)) |

### 📦 HTB CWES (ex CBBH)

| | |
|---|---|
| 🧪 **Format** | 🛠️ Web-Pentest/Bug-Bounty auf mehreren Apps + Report ✅ [HTB Certs](https://academy.hackthebox.com/preview/certifications) |
| 🔁 **Namenswechsel** | CBBH → CWES per 01.10.2025, Inhaber automatisch umgestellt 🟦 [HTB News](https://academy.hackthebox.com/news/the-transition-from-htb-cbbh-to-htb-cwes-has-officially-started) |
| 🎓 **Voraussetzungen** | Path „Web Penetration Tester“ (**20 Module**) ✅ |
| 💰 **Preis** | 210 USD / Silver Annual ✅ |
| ⏳ **Lernaufwand** | PWN PATH ~191 h 🟦 |
| 🌶️ **Schwierigkeit** | 🌶️🌶️🌶️ ⚠️ |

### 📦 HTB CDSA

| | |
|---|---|
| 🧪 **Format** | 🛠️ SOC-Analyse & Incident Handling, Report ✅ [HTB Certs](https://academy.hackthebox.com/preview/certifications) |
| 🎓 **Voraussetzungen** | Path (15 Module) ✅ |
| 💰 **Preis** | 210 USD / Silver Annual ✅ |
| ⏳ **Lernaufwand** | PWN PATH ~128 h 🟦 |
| 🧭 **Hinweis** | Ideal, wenn du im Fachausweis-Kontext auch die Verteidigerseite belegen willst |

### 📦 HTB CWEE

| | |
|---|---|
| 🧪 **Format** | 🛠️ Fortgeschrittenes Web (Black- **und** White-Box, Code-Review, Exploit-Entwicklung) ✅ [HTB Certs](https://academy.hackthebox.com/preview/certifications) |
| ⏱️ **Prüfung** | 10 Tage; ≥ 5 von 6 Flags + Report (Markdown-ZIP) 🟦 [MindPatch](https://cnmoseman.github.io/htb-study-trackers/cwee/tracker/) |
| 💰 **Preis** | **350 USD** oder Gold Annual 1'400 USD (Silver-Voucher **nicht** tauschbar in CWEE ✅ [Voucher-Tausch](https://help.hackthebox.com/en/articles/12741804-swapping-exam-voucher)) |
| ⏳ **Lernaufwand** | PWN PATH ~191 h 🟦 (⚠️ wirkt niedrig für „Expert“) |
| 🌶️ **Schwierigkeit** | 🌶️🌶️🌶️🌶️🌶️ ⚠️ |

### 📦 HTB CAPE

| | |
|---|---|
| 🧪 **Format** | 🛠️ Fortgeschrittenes AD: Kerberos/NTLM-Abuse, ADCS, WSUS, Exchange, Trusts, C2 ✅ [HTB Certs](https://academy.hackthebox.com/preview/certifications) |
| ⏱️ **Prüfung** | 10 Tage, 90 Punkte aus Flags + Report 🟦 [HTB Blog](https://www.hackthebox.com/blog/htb-cape-exam-explained-pentest-job-role-path-certification) |
| 💰 **Preis** | **350 USD** / Gold Annual ✅ |
| ⏳ **Lernaufwand** | PWN PATH ~196 h 🟦 |
| 🌶️ **Schwierigkeit** | 🌶️🌶️🌶️🌶️🌶️ ⚠️ |

### 📦 HTB CJCA

| | |
|---|---|
| 🧪 **Format** | 🛠️ Hybrid: Grundlagen Offensive **und** SIEM-gestützte Defensive ✅ [HTB Certs](https://academy.hackthebox.com/preview/certifications) |
| 💰 **Preis** | **105 USD**; in Silver/Gold Annual **zusätzlich** enthalten ✅ |
| ⏳ **Lernaufwand** | PWN PATH ~210 h 🟦 |
| 🧭 **Hinweis** | Guter „Gratis-Bonus“ im Silver-Annual-Abo – kein eigenständiger Kaufgrund ⚠️ |

---

## 🧑‍🏫 TCM Security

> **Gemeinsam (✅ [certifications.tcm-sec.com](https://certifications.tcm-sec.com/)):** Jeder Voucher enthält **12 Monate Kurszugang** + **1 Gratis-Retake**; **kein Proctoring**; 20 % Rabatt für Militär, Veteranen, Studierende, Lehrkräfte, Ersthelfer. Learning-Path-Bundles kombinieren z. B. PJPT + PNPT + PORP.

### 🧑‍🏫 PJPT

| | |
|---|---|
| 🧪 **Format** | 🛠️ Interner **AD-Pentest** auf Associate-Niveau ✅ [PJPT](https://certifications.tcm-sec.com/pjpt/) |
| ⏱️ **Prüfung** | **2 Tage** Test + **2 Tage** Report ✅ |
| 💰 **Preis** | **249 USD** (inkl. Kurs „Practical Ethical Hacking“, 20+ h) ✅ |
| 🔄 **Gültigkeit** | „does NOT expire“ ✅ |
| ⏳ **Lernaufwand** | ⚠️ eigene Schätzung: 60–120 h bei IT-Grundlagen (Kurs 20+ h ✅ + Übung) |
| 🌶️ **Schwierigkeit** | 🌶️🌶️ ⚠️ |
| 🧭 **Lernstrategie** | Bester **erster** Schein für dich neben dem HF-Start: realistisch, günstig, Report-Pflicht. AD-Lab parallel auf dem Cluster nachbauen ([Homelab](homelab-practice.md)) |

### 🧑‍🏫 PNPT

| | |
|---|---|
| 🧪 **Format** | 🛠️ **Extern + intern** inkl. OSINT bis Domain Admin, danach **15-min-Live-Debrief** 🟦 [immunitysec](https://www.immunitysec.com/certifications/pnpt/) |
| ⏱️ **Prüfung** | **5 Tage** + **2 Tage** Report ✅ [PNPT](https://certifications.tcm-sec.com/pnpt/) |
| 💰 **Preis** | **499 USD** inkl. 45+ h Training ✅ |
| 🔄 **Gültigkeit** | „As of 04/17/2023 … does NOT expire“ ✅ |
| ⏳ **Lernaufwand** | PWN PATH ~172 h 🟦 |
| 🌶️ **Schwierigkeit** | 🌶️🌶️🌶️ ⚠️ |
| 🏢 **Anerkennung** | In der Community sehr geschätzt (realistisch, Debrief); in klassischen HR-Filtern weniger bekannt als OSCP ⚠️ |
| 🧭 **Lernstrategie** | Debrief üben: 15 min Befunde mündlich erklären – trainiert genau das, was Kunden wollen |

---

## 🎓 INE

> **Gemeinsam (✅ [ine.com](https://ine.com/fundamentals-vs-premium)):** Für jede Prüfung brauchst du **Abo + Voucher**. **Fundamentals Annual 349 USD/Jahr** inkl. **1 Gratis-Voucher** (eJPT oder ICCA) · **Premium 799 USD**. Voucher verfallen **180 Tage** nach Kauf; 1 Gratis-Retake innerhalb von 14 Tagen; Zertifikate **3 Jahre** gültig ✅ [eJPT](https://security.ine.com/certifications/ejpt-certification/). Profi-Voucher (eCPPT, eWPT, eCTHP, eMAPT …) **nur mit Premium** ✅ [eCPPT](https://security.ine.com/certifications/ecppt-certification/). Voucher-Preis ⚠️: Drittquellen nennen 450 USD (Pro) bzw. 249 USD (eJPT) 🟦.

### 🎓 eJPT

| | |
|---|---|
| 🧪 **Format** | 🧩 Praktisches Lab, Fragen werden aus deinen Funden beantwortet; **auto-graded** ✅ [eJPT](https://security.ine.com/certifications/ejpt-certification/) |
| ⏱️ **Prüfung** | ~**48 h**-Fenster, ~35 Fragen 🟦 [InfoSec Write-ups](https://hackerdna.com/blog/ejpt-certification) |
| 📝 **Report** | ❌ |
| 💰 **Preis** | Fundamentals Annual **349 USD** (inkl. Voucher) ✅ · Voucher allein ~249 USD 🟦 |
| 🔄 **Gültigkeit** | **3 Jahre** ✅ |
| ⏳ **Lernaufwand** | PWN PATH ~84 h 🟦 · Erfahrungsbericht **73 h** 🟦 [time0ut](https://www.time0ut.com/posts/blogs/ctrl_alt_certified.html) |
| 🌶️ **Schwierigkeit** | 🌶️🌶️ ⚠️ |
| 🧭 **Lernstrategie** | Gute „Methodik-Schule“ (Enumeration, Pivoting, Metasploit); kein Report → Report-Schreiben separat üben |

### 🎓 eCPPT

| | |
|---|---|
| 🧪 **Format** | 🧩 Seit **v3 (2024)**: ~24-h-Prüfung mit ~45 Lab-Fragen statt 7-Tage-Report 🟦 [r/eLearnSecurity](https://www.reddit.com/r/eLearnSecurity/comments/1dk0sn9/ecppt_v3/) · auto-graded ✅ [eCPPT](https://security.ine.com/certifications/ecppt-certification/) |
| 💰 **Preis** | Premium 799 USD + Voucher ⚠️ |
| 🔄 **Gültigkeit** | 3 Jahre ✅ |
| ⏳ **Lernaufwand** | PWN PATH ~251 h 🟦 |
| ⚠️ **Ehrlich** | Ältere Reviews beschreiben das **alte** Report-Format – nicht verwechseln |

### 🎓 eWPT

| | |
|---|---|
| 🧪 **Format** | 🧩 Praktisch, auto-graded ✅ [eWPT](https://security.ine.com/certifications/ewpt-certification/) · Dauer/Fragenzahl öffentlich nicht angegeben ⚠️ (Community: ~50 Fragen, ~10 h 🟦 [FlashGenius](https://flashgenius.net/blog-article/ewpt-certification-the-ultimate-2026-guide)) |
| 💰 **Preis** | Premium + Voucher ⚠️ |
| 🔄 **Gültigkeit** | 3 Jahre ✅ |
| 🧭 **Hinweis** | Für Web bieten BSCP/CWES aus unserer Sicht mehr Lernwert pro Franken ⚠️ |

---

## 🏰 Altered Security

> **Gemeinsam (✅ [alteredsecurity.com](https://www.alteredsecurity.com/adlab)):** Preis hängt von der **Lab-Dauer** ab (30/60/90 Tage), Kursmaterial **lebenslang**, 1 Prüfungsversuch inkl., Retake **99 USD** (1 Monat Cooldown); Zertifikate **3 Jahre** gültig, **Renewal-Prüfung gratis** vor Ablauf. Früher via **Pentester Academy** verkauft → [Hidden Gems](hidden-gems.md#-pentester-academy-legacy).

### 🏰 CRTP

| | |
|---|---|
| 🧪 **Format** | 🛠️ AD-Angriffe **ohne patchbare Exploits** (Feature-Abuse) ✅ [CRTP](https://www.alteredsecurity.com/adlab) |
| ⏱️ **Prüfung** | **24 h** Hands-on ✅ + Report (Frist 48 h 🟦 [PWN PATH](https://thepwnpath.win/which-cert-should-i-take/)) |
| 💰 **Preis** | **249 / 379 / 499 USD** (30/60/90 Tage) ✅ |
| 🔄 **Gültigkeit** | 3 Jahre, Renewal-Prüfung gratis ✅ |
| ⏳ **Lernaufwand** | Video 14+ h ✅ · PWN PATH ~124 h 🟦 · Erfahrungsbericht **92 h** (ohne AD-Vorwissen) 🟦 [time0ut](https://www.time0ut.com/posts/blogs/ctrl_alt_certified.html) |
| 🌶️ **Schwierigkeit** | 🌶️🌶️🌶️ ⚠️ |
| 🏢 **Anerkennung** | In Red-Team-Kreisen sehr bekannt; extrem gutes Preis-Leistungs-Verhältnis 🟦 |
| 🧭 **Lernstrategie** | Zuerst **eigenes AD-Lab** (GOAD) bauen und verstehen, *dann* 30-Tage-Lab kaufen → spart Geld ([Homelab](homelab-practice.md)) |

### 🏰 CRTE

| | |
|---|---|
| 🧪 **Format** | 🛠️ Enterprise-AD, Multi-Domain/-Forest, voll gepatcht ✅ [CRTE](https://www.alteredsecurity.com/redteamlab) |
| ⏱️ **Prüfung** | **48 h** ✅ + Report |
| 💰 **Preis** | **299 / 499 / 699 USD** ✅ |
| 🔄 **Gültigkeit** | 3 Jahre, Renewal gratis ✅ |
| ⏳ **Lernaufwand** | PWN PATH ~186 h 🟦 · Erfahrungsbericht 53 h (nach CRTP+OSCP+CRTO) 🟦 [time0ut](https://www.time0ut.com/posts/blogs/ctrl_alt_certified.html) |
| 🌶️ **Schwierigkeit** | 🌶️🌶️🌶️🌶️ ⚠️ |

---

## 🎯 Zero-Point Security

> **Gemeinsam (✅ [zeropointsecurity.co.uk](https://www.zeropointsecurity.co.uk/course/red-team-ops)):** **Lebenslanger** Kurs- und Lab-Zugang ohne Ablauf, **beliebig viele Gratis-Prüfungsversuche** („no financial penalty for failing“). Preise in **GBP**.

### 🎯 CRTO

| | |
|---|---|
| 🧪 **Format** | 🛠️ Adversary Simulation mit **Cobalt Strike** (Lizenz im Lab enthalten) ✅ [RTO](https://www.zeropointsecurity.co.uk/course/red-team-ops) |
| ⏱️ **Prüfung** | Neues Format (2025/26): 24 h aktive Lab-Zeit, pausierbar über 7 Tage; Bewertung Ziel + **OPSEC** 🟦 [payloadforge](https://payloadforge.io/crto-lifetime-access-to-a-course-that-doesnt-exist-any-more/) |
| 💰 **Preis** | **399 GBP** ≈ 529 USD ≈ 441 CHF ✅/⚠️ (Umrechnung) |
| 🔄 **Gültigkeit** | Läuft nicht ab 🟦 [immunitysec](https://www.immunitysec.com/certifications/crto/) |
| ⏳ **Lernaufwand** | Anbieter „Study time: 20 hours“ ✅ (nur Material) · PWN PATH ~151 h 🟦 · Erfahrungsbericht 67 h 🟦 [time0ut](https://www.time0ut.com/posts/blogs/ctrl_alt_certified.html) |
| 🌶️ **Schwierigkeit** | 🌶️🌶️🌶️ ⚠️ |
| ⚠️ **Ehrlich** | Kurs wurde grundlegend überarbeitet – alte Reviews (48-h-CTF, 6/8 Flags) gelten nicht mehr 🟦 [payloadforge](https://payloadforge.io/crto-lifetime-access-to-a-course-that-doesnt-exist-any-more/) |

### 🎯 CRTL (ex „CRTO II“)

| | |
|---|---|
| 🧪 **Format** | 🛠️ „Red Team Ops II“ → Zertifikat **Red Team Lead** (EDR-/Defender-Evasion, fortgeschrittene Tradecraft) ✅ [RTO II](https://www.zeropointsecurity.co.uk/course/red-team-ops-ii) |
| 💰 **Preis** | **449 GBP** ≈ 596 USD ✅/⚠️ |
| ⏳ **Lernaufwand** | Anbieter „Study time: 12 hours“ ✅ (nur Material, ⚠️ real deutlich mehr) |
| 🔁 **Name** | Früher als „CRTO II“ bekannt ⚠️ (Community-Bezeichnung; auf der Kursseite heute „Red Team Lead“) |
| 🌶️ **Schwierigkeit** | 🌶️🌶️🌶️🌶️🌶️ ⚠️ |

---

## 🏛️ GIAC / SANS

> **Gemeinsam (✅ [giac.org/pricing](https://www.giac.org/pricing)):** Attempt **999 USD** (ohne Kurs), Retake 899, Verlängerung 479, Practice Exam 399 USD; Renewal **499 USD** alle **4 Jahre** + **36 CPE** ✅ [GIAC Renewal](https://www.giac.org/renewal). Fenster: **120 Tage** ab Aktivierung, proctored (ProctorU oder Pearson VUE) ✅. Der passende **SANS-Kurs** kostet z. B. SEC560 OnDemand **8'780 USD** ✅ [SANS SEC560](https://www.sans.org/cyber-security-courses/enterprise-penetration-testing). Laut Community sind GIAC-Prüfungen **Open Book** mit gedruckten Unterlagen (eigener Index!) ⚠️ – aktuelle Prüfungsregeln vorher bei GIAC prüfen.

### 🏛️ GPEN

| | |
|---|---|
| 🧪 **Format** | 🧩 82 Fragen inkl. **CyberLive** (Hands-on-Aufgaben in echten VMs) ✅ [GPEN](https://www.giac.org/certifications/penetration-tester-gpen) |
| ⏱️ **Prüfung** | **3 h**, 73 % zum Bestehen ✅ |
| 💰 **Preis** | 999 USD (+ SANS SEC560) ✅ |
| 🏢 **Anerkennung** | DoD 8140 Rolle 541 bis **Advanced** 🟦 [Matrix-Auszug](https://www.immunitysec.com/certifications/dod-8140/541/) |
| ⏳ **Lernaufwand** | ⚠️ eigene Schätzung: Kurs (6 Tage) + 40–80 h Indexing/Übung |

### 🏛️ GXPN

| | |
|---|---|
| 🧪 **Format** | 🧩 60 Fragen, 3 h, 67 % ✅ [GXPN](https://www.giac.org/certifications/exploit-researcher-advanced-penetration-tester-gxpn/) |
| 💰 **Preis** | 999 USD (+ SANS SEC660) ✅ |
| 🌶️ **Schwierigkeit** | 🌶️🌶️🌶️🌶️ ⚠️ |

### 🏛️ GWAPT

| | |
|---|---|
| 🧪 **Format** | 🧩 82 Fragen, 3 h, 71 % ✅ [GWAPT](https://www.giac.org/certifications/web-application-penetration-tester-gwapt/) |
| 💰 **Preis** | 999 USD (+ SANS SEC542) ✅ |

### 🏛️ GCIH

| | |
|---|---|
| 🧪 **Format** | 🧩 106 Fragen, 4 h, 69 % ✅ [GCIH](https://www.giac.org/certifications/certified-incident-handler-gcih/) |
| 💰 **Preis** | 999 USD (+ SANS SEC504) ✅ |
| 🏢 **Anerkennung** | DoD 8140 Rolle 541 (Basic/Intermediate) 🟦; Klassiker für Incident Handler |

---

## 🧾 CompTIA

> **Gemeinsam:** Gültigkeit **3 Jahre**; Renewal via CEUs + **CE-Gebühr 150 USD pro 3 Jahre** (Security+, PenTest+) – entfällt bei Neuprüfung oder höherem Zertifikat ✅ [CompTIA CE](https://www.comptia.org/en-us/resources/ce/learn/continuing-education-renewal-fees/). **Voucher-Preis** auf der CompTIA-Seite bei unserem Abruf nicht maschinenlesbar ⚠️ – Drittquellen nennen **~439 USD** (mit Retake ~579 USD) 🟦 [Exam Atlas](https://globalexamatlas.com/en/exams/cybersecurity/comptia-pentest-plus/cost/).

### 🧾 CompTIA Security+

| | |
|---|---|
| 🧪 **Format** | 🧩 MC + Performance-Based Questions |
| 📅 **Version** | V7 (SY0-701) aktuell; **V8 ab ca. 17.11.2026** ✅ [CompTIA](https://www.comptia.org/en-us/certifications/security/) |
| ⏳ **Lernaufwand** | Reddit: ~40–120 h, oft 3–4 Wochen 🟦 [r/CompTIA](https://www.reddit.com/r/CompTIA/comments/1lbhhqz/how_long_did_you_study_for_security/) |
| 🏢 **Anerkennung** | DoD 8140 Rolle 541 bis Intermediate 🟦 |
| 🧭 **Hinweis** | **Kein Hacker-Zertifikat**, sondern Security-Grundlagen. Für dich: Inhalte überschneiden sich stark mit der HF/Fachausweis-Theorie ⚠️ → nur kaufen, wenn ein Arbeitgeber es verlangt |

### 🧾 CompTIA PenTest+

| | |
|---|---|
| 🧪 **Format** | 🧩 PT0-003: max. **90 Fragen** (MC + PBQ), **165 min**, 750/900 Punkte ✅ [CompTIA PenTest+](https://www.comptia.org/en-us/certifications/pentest/) |
| 📅 **Version** | Launch 17.12.2024; Ablösung voraussichtlich 2027 ✅ |
| 🏢 **Anerkennung** | DoD 8140 Rolle 541 (Basic/Intermediate) 🟦 |
| 🧭 **Hinweis** | Wissensprüfung – beweist kein Hands-on-Können ⚠️ |

---

## 🎩 CEH & CEH Practical

| | |
|---|---|
| 🧪 **Format** | **CEH:** 📝 125 MC, 4 h ✅ [Digicomp](https://digicomp.ch/courses-cyber-security/offense-testing/course-ec-council-certified-ethical-hacker-v13-ceh-cehb) · **CEH Practical:** 🛠️ 20 Challenges, **6 h**, iLabs, 70 % ✅ [EC-Council iClass](https://iclass.eccouncil.org/our-courses/certified-ethical-hacker-ceh/) · beide = „CEH Master“ |
| 🎓 **Voraussetzungen** | Offizielles Training **oder** 2 Jahre Erfahrung + **100 USD** Eligibility-Gebühr ✅ [EC-Council](https://www.eccouncil.org/train-certify/certified-ethical-hacker-ceh/) |
| 💰 **Preis** | Kurs ab **1'699 USD** (On-Demand) ✅ · Voucher **950 USD** (remote) / **1'199 USD** (Pearson VUE) 🟦 [immunitysec](https://www.immunitysec.com/certifications/ceh/) · Practical **550 USD** ✅ [EC-Council Store](https://store.eccouncil.org/product/ceh-practical-exam/) · CH: Digicomp **CHF 6'200** exkl. MWST (5 Tage, Voucher + Retake) ✅ |
| 🔄 **Gültigkeit** | 3 Jahre, 120 ECE-Credits + **80 USD/Jahr** 🟦 |
| 🌶️ **Schwierigkeit** | CEH 🌶️🌶️ · Practical 🌶️🌶️ ⚠️ |
| 🏢 **Anerkennung** | Sehr bekannt bei HR/Behörden (DoD 8140: CEH Basic, CEH(P) bis Intermediate 🟦); in Pentest-Teams eher **gering** geschätzt ⚠️ |
| 🧭 **Ehrlich** | Hohes Preis-/Praxisverhältnis. Nur sinnvoll, wenn eine Ausschreibung/Behörde es **explizit** verlangt ⚠️ |

---

## 🌐 BSCP (Burp Suite Certified Practitioner)

| | |
|---|---|
| 🧪 **Format** | 🛠️ **2 verwundbare Apps** à 3 Stufen (Zugang → Admin → Datei lesen), Burp Suite Pro Pflicht ✅ [How it works](https://portswigger.net/web-security/certification/how-it-works) |
| ⏱️ **Prüfung** | **4 h** ✅ |
| 💰 **Preis** | **99 USD** pro Versuch 🟦 [PortSwigger Blog](https://portswigger.net/blog/introducing-the-burp-suite-certified-practitioner-accreditation) + aktive **Burp Suite Pro**-Lizenz (Kaufseite: 499 USD ✅ [Burp Pro](https://portswigger.net/burp/pro)) |
| 🔄 **Gültigkeit** | **5 Jahre** ✅ [BSCP](https://portswigger.net/web-security/certification) |
| ⏳ **Lernaufwand** | PWN PATH ~166 h 🟦; Lernstoff (Web Security Academy) **gratis** |
| 🌶️ **Schwierigkeit** | 🌶️🌶️🌶️🌶️ – Zeitdruck 🟦 [Jael Koh](https://infosec.jaelkoh.com/2024/my-first-year-in-infosec-zero-to-osce3) |
| 🧭 **Lernstrategie** | Alle „Practitioner“-Labs der Academy lösen (offizielle Empfehlung ✅ [FAQ](https://portswigger.net/web-security/certification/frequently-asked-questions)); Mystery-Labs; eigene Checkliste pro Stufe; Burp Pro erst kurz vor der Prüfung kaufen (spart Geld ⚠️) |

---

## 🇬🇧 CREST: CPSA → CRT → CCT INF / CCT APP

| | |
|---|---|
| 💰 **Preise** | **CPSA 275 GBP** · **CRT 600 GBP** · **CCT INF / CCT APP je 1'600 GBP** (2 Teile, separat buchen) – exkl. MWST ✅ [CREST Pricing](https://www.crest-approved.org/skills-certifications-careers/certifications-pricing-booking/) |
| 🧪 **CRT** | 🧩 MC + Flags + Kurzantworten, **eigenes Kali im Pearson-VUE-Testcenter** (kein eigener Laptop), **2.5 h** + 15 min Lesezeit; ≥ 60 % in Infrastruktur **und** Web; **CPSA Voraussetzung**; Retake nach 8 Wochen ✅ [CRT](https://www.crest-approved.org/skills-certifications-careers/crest-registered-penetration-tester/) |
| 🧪 **CCT INF** | Schriftlich **3 h** (1 h MC + 2 h Szenario/Report-Analyse, closed book) + praktisch **3 h**; keine Voraussetzungen ✅ [CCT INF](https://www.crest-approved.org/skills-certifications-careers/crest-certified-infrastructure-tester/) |
| 🧪 **CCT APP** | analog für Web-Apps ✅ [CCT APP](https://www.crest-approved.org/skills-certifications-careers/crest-certified-web-application-tester/) |
| 🔄 **Gültigkeit** | CRT/CPSA 3 Jahre 🟦 [CRT FAQ](https://www.crest-approved.org/skills-certifications-careers/crt-faqs/) |
| 🏢 **Anerkennung** | CRT von UK-NCSC für **CHECK** anerkannt ✅; stark in UK, Australien, Asien; in der Schweiz ⚠️ selten gefordert (eigene Beobachtung, nicht systematisch geprüft) |
| 🌶️ **Schwierigkeit** | CRT 🌶️🌶️🌶️ · CCT 🌶️🌶️🌶️🌶️🌶️ ⚠️ |

---

[← zurück zur Übersicht](../README.md) · [💰 Preise](prices.md) · [⏱️ Lernaufwand](study-effort.md) · [💎 Hidden Gems](hidden-gems.md)
