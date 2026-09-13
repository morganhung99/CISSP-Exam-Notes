# Passing the CISSP: From Engineer to Security Leader

### Study strategy, the CAT exam in practice, and the key points across all eight domains

---

## Preface: The Road Every Security Leader Walks

Let's start with what everyone already knows about the CISSP. It does not test how well you write code, how deeply you understand firmware analysis, or whether you can type a flawless penetration testing command into a terminal. It tests whether you can **translate technical risk into business language**, and strike the right balance between compliance, budget, and operational value.

> **Field Note**
>
> That said, this time around I got roughly three to five questions that were straight technical-term definitions. I thought about each for about two seconds and guessed. So technical knowledge still matters.
>
> For the record: I sat the exam in Simplified Chinese with English as the secondary display language, and bought the two-attempt package — though I passed on the first try.

This is a long write-up, organised with the help of AI, covering what I learned while preparing. Whether you are a technical professional moving into management or an executive who needs to see the whole board, I hope it saves you some detours.

---

## Chapter 1 — Mindset: From Engineer to CISO

The most common problem people with strong technical backgrounds hit when they first open a CISSP question bank is simple: **they are answering from the wrong perspective.** In the CISSP worldview, remember two things — think at altitude, and advise rather than act.

### 1. The Two Iron Rules

**Human life and safety always come first.** This is the one rule in the CISSP with no exceptions. No matter how classified the data or how expensive the server, when you face fire, intrusion, or a physical threat, **protecting people is always the first priority**. Any option that sacrifices human safety to preserve assets is wrong. Every time.

**Policy outranks everything.** Between a technical solution and a management policy, policy is always the higher authority. Policy represents the will of senior management and the compliance obligation; technology is merely the means of implementing it.

### 2. The Four Canons of the ISC2 Code of Ethics

Ethical dilemmas appear regularly as traps. Memorise these in order of precedence and apply them that way — when two conflict, the earlier one wins:

1. Protect society, the common good, necessary public trust and confidence, and the infrastructure. *(For example: when you find a vulnerability that could endanger the public, public safety outranks the company's commercial interest.)*
2. Act honourably, honestly, justly, responsibly, and legally.
3. Provide diligent and competent service to principals. *(For example: only take on projects you are actually competent to deliver.)*
4. Advance and protect the profession.

### 3. The Core of "Think Like a Manager"

**Business value comes above all else.** Security exists to support business objectives and create value, not to be secure for its own sake. When the annual cost of a control exceeds the loss it actually reduces, or when the control seriously obstructs operations, it is not the best answer.

**Understand information systems audit and internal control.** A modern CISO needs audit thinking. Driving an ISO 27001 certification, designing automated audit templates, building an ESG assessment framework for IT equipment energy consumption to satisfy an international standard — all of these sit under governance, risk, and compliance. GRC is the top-level logic the exam loves most.

**Advise, don't touch.** When a scenario describes a server under attack, the engineer's instinct is to pull the network cable or start reading logs. But in CISSP logic you are the external consultant or the CISO. Your move comes from the management side: confirm whether the incident response plan has been activated, report the risk to senior management, isolate the network while preserving business continuity.

---

## Chapter 2 — Resources and a Systematic Study Plan

The Common Body of Knowledge spans eight domains and is genuinely large. I'd suggest a systematic sequence:

**Build a foundation → read other people's write-ups → drill questions → patch weak areas → drill again → then repeat the last two steps indefinitely.**

> **Field Note**
>
> In practice, all I did was find study material on GitHub, read through it once, then start generating questions with AI, patch my weaker domains, and drill relentlessly.
>
> One thing worth stressing: **when searching online, restrict yourself to material from the last two to three years.** Anything older has essentially no reference value now.

### 1. Core Setup: Textbook and Question Bank

**Textbook.** Most write-ups recommend the *CISSP Official Study Guide (OSG)*. If you can buy it, it will help you build a solid foundation. The usual advice is to skim headings and bold text on the first pass, building a mental index of the concepts, then deep-dive the unfamiliar domains such as cryptography and security architecture on the second pass.

> **Field Note**
>
> I went a different route and searched for material generously shared by the community. What I mainly used was [lorenzoleonelli/CISSP-Zero-to-Hero](https://github.com/lorenzoleonelli/CISSP-Zero-to-Hero), because the content looked current, it is actively maintained, and it covers recent topics such as AI and post-quantum cryptography. One read-through, then drilling, then back to patch the weaker domains.

**Question banks.** The commonly recommended options are the *Official Practice Tests (OPT)*, Pocket Prep, and Boson. The point of drilling is **not to memorise answers**. It is to train your brain, across several hundred questions, to build **pattern recognition**.

> **Field Note**
>
> There are plenty of question banks out there, but I didn't buy one. I took a few community-shared sets as templates, fed them to AI to generate mock exams, and just drilled.
>
> The detail that made this work: **I used five different AI tools, 100 questions at a time.** The benefit is much broader domain coverage than any single tool gives you. I did roughly 700 questions in total, scoring between 75% and 85% each round.

**Notes.** Turn easily confused concepts into comparison tables — the trade-offs between symmetric and asymmetric encryption, the access control security models, attack techniques and their countermeasures. The point is simply to capture key material as bullet points or tables while you read, so revision is fast later.

> **Field Note**
>
> Anything I had never encountered before went into a table, which I printed on paper and left on my desk to glance at whenever I had a spare minute. The read-up / write-down, write-up / read-down rules in particular — I just pulled out the keywords and stared at them. About three days and they stuck.

### 2. Supplementary Resources

**Pete Zerger — CISSP Exam Cram series.** Recommended for commutes and dead time. He distils high-probability topics and difficult concepts efficiently. *This is a community recommendation; I didn't use it.*

**Kelly Handerhan — Why You Will Pass the CISSP.** The classic pre-exam mindset video, good for easing anxiety and calibrating your answering perspective. *Also a community recommendation; I didn't watch it either.*

**Question breakdown drills.** When practising, work through this sequence:

1. Read the question at least once, then scan the answers.
2. Read the question again.
3. Identify which domain it belongs to.
4. Mark the qualifier — FIRST, BEST, MOST, LEAST LIKELY.
5. Work out what core concept is actually being tested. Specifically: if you were the CISO or a C-level executive, what would you think and do? Apply the principles above.
6. Look at the answers once more, think, and commit. Don't linger. If it won't resolve, guess — exam time is a critical constraint.

**Other supplementary material.** Mainly current technology, regulation, and standards. I've put those at the end of this article.

### 3. The 80/20 Review Rule

Don't waste time on domains you already know well. Put 80% of your energy into the ones you don't.

> **Field Note**
>
> After one or two rounds of drilling, my weak domains were clearly D1, D5, D6, and D8, so those got the extra passes.
>
> One more thing, which I'd recommend to anyone who hasn't sat an exam in a long time. Because it had genuinely been years for me, over four months (May to August) I deliberately sat three smaller certifications as warm-ups: Taiwan's IPAS Level 1 and Level 2 information security certifications, and ISC2's Certified in Cybersecurity (CC). The goal was to re-learn the rhythm and mechanics of taking an exam — around 50 questions each, finished in about an hour, all passed.

---

## Chapter 3 — The Exam Room and the CAT Format

Finish one full mock exam and your last pass over key points and weak areas **1.5 days before** the exam. Then go in with a settled mind. The CISSP is not only a test of security knowledge — it is also a test of composure. A stable mood and sustained stamina are a significant part of it.

### 1. CAT (Computerised Adaptive Testing)

The exam is now fully adaptive. Keep these characteristics in mind so nothing throws you on the day:

**Question count and time.** Between 100 and 150 questions, with a hard ceiling of 3 hours (180 minutes).

**No going back.** Once an answer is submitted it is **locked**. You cannot return, cannot revise, cannot flag for later. So before you press Next, make sure you have deliberately chosen the best or most appropriate of the four options.

**Non-linear scoring and dynamic difficulty.** The system continuously re-estimates your ability from your answers. Answer correctly and the questions get harder — including plenty of scenarios and technical terms you've never seen. (I hit several, and simply guessed on a few of them.) **If the questions get hard enough to make you question your life choices, congratulations — that usually means you're doing very well.**

**Hidden beta items.** Twenty-five unscored pretest questions are mixed into the exam to evaluate future items. You cannot tell which ones they are, so give every question your full effort.

### 2. Time Management in Practice

Since you cannot know whether you'll finish at question 100 or question 150, **time management is the only weapon fully under your control.**

**Budget 1.2 to 2 minutes per question.** When you hit something you don't know, eliminate the obviously wrong distractors quickly, pick whichever remaining option best fits the management mindset, and move forward. Never get stuck on one question for five minutes.

> **Field Note**
>
> Somewhere around the halfway point you'll find yourself glancing at the question counter, especially near the end. My advice is to stop looking. What matters is keeping each question under two minutes.
>
> I took about two hours — went in just before 2pm, walked out around 3:40pm. Looking back at the mix: roughly 20% were pure instinct, 30% I could reason out from knowledge, another 20% I answered from work experience, and the remaining 30% I wasn't confident about at all.
>
> I passed question 100 and it didn't stop. Let's just say a stampede of colourful language went through my head, and I kept checking the counter. By question 110 it was getting annoying, so I gave up looking and focused on answering. **Then at question 115 it just ended.** Abruptly. And honestly I felt a little deflated — *that's it?*

### 3. When All Four Look Wrong (or All Four Look Right)

The CISSP loves asking you to select the BEST or MOST appropriate answer.

**When every option looks wrong:** pick the **least incorrect** one.

**When every option looks right:** look for the **universal, higher-level, widest-scope** answer. If options A, B, and C are all specific technical actions and option D is a higher-level management policy, D is usually correct — because D is the foundation on which A, B, and C would be implemented. Again, remember the principles from the start of this article.

> **Field Note**
>
> A lot of scenarios present several answers that all look plausible, which is exactly why your concepts have to be built solidly and correctly during preparation, not approximately.
>
> One small thing that may help on the day: **keep your emotional state flat.** If you hit a run of questions you're unsure about, take a few deep breaths and stretch a little — nothing dramatic — then re-read the question and options carefully and reason your way to the best answer. Because of how CAT works, it will feed you waves of boss-level questions specifically designed to dent your confidence. Just tell yourself: worst case, I don't pass this time and I prepare again. Nobody has to know.

When it's over, collect the printed result at the desk, flip it over immediately, and read it. Then go home in a good mood and do absolutely nothing for a while.

What follows is the set of key points I organised with AI. I hope it helps.

---

## Chapter 4 — Domains 1 to 4 in Depth

To get into the core knowledge of the CISSP, you have to switch your perspective from technology to governance and risk. What follows distils the most common traps, the management decision logic, and how each maps to technical implementation.

### Domain 1 — Security and Risk Management

The highest-weighted domain at 16%, and the foundation of the whole certification. Every technical control ultimately exists to support business objectives and risk governance.

**1. Policy document hierarchy**

Questions frequently test whether you can pick the right document type for a given situation. Remember: **only Guidelines are non-mandatory.**

- **Policy** — Mandatory. High-level, principle-based, technology-agnostic, approved by senior management. *"All sensitive data in this company must be encrypted."*
- **Standard** — Mandatory. Specifies concrete hardware, software, and technical requirements. *"AES-256 must be used."*
- **Baseline** — Mandatory. The minimum security or configuration requirement all organisational systems must meet. *"All servers must comply with CIS Benchmark Level 1."*
- **Procedure** — Mandatory. Detailed step-by-step instructions. *"The ten specific steps of key rotation."*
- **Guideline** — Recommended. Non-mandatory best practice offering flexibility. *"Review permissions quarterly."*

**2. Due Diligence vs. Due Care**

Management that fails to exercise both is legally **negligent**.

- **Due Diligence — investigate first.** Researching and understanding the risk. For example, reviewing a vendor's SOC 2 report before signing.
- **Due Care — act second.** Actually implementing controls. For example, deploying the firewall and encryption based on what the investigation found.

**3. Quantitative risk assessment in financial language**

To persuade management to invest in security, you have to convert risk into money.

- **SLE** (Single Loss Expectancy) = **AV** (Asset Value) × **EF** (Exposure Factor)
- **ALE** (Annualised Loss Expectancy) = **SLE** × **ARO** (Annualised Rate of Occurrence)
- **The decision rule:** if (ALE before the control − ALE after the control) is less than the annual cost of that control, the control is not worth the investment, and the organisation should consider accepting the risk. Residual risk must be formally signed off by the business owner.

**4. Threat modelling**

Most valuable when performed at the **design stage**, because remediation cost rises exponentially through the development lifecycle.

- **STRIDE** — system-centric, mapping each threat to the security property it breaks. Spoofing maps to authenticity, Tampering to integrity, Repudiation to non-repudiation.
- **PASTA** — attacker- and business-risk-centric, with seven stages. The first step is always defining business objectives.
- **LINDDUN** — privacy threat modelling, addressing linkability, identifiability, and unawareness, the core concerns of GDPR.

### Domain 2 — Asset Security

Roughly 10% of the exam. The core is working out what we have (inventory), how important it is (classification), and how to handle and destroy it safely (protection).

**1. Roles and responsibilities**

**Never let the IT department decide data classification levels.** This is a recurring trap.

- **Data Owner** — usually a senior business manager, carrying ultimate organisational and legal responsibility, and holding final decision authority over the classification level.
- **Data Custodian** — an IT administrator or DBA, responsible for technical implementation such as backup and encryption, with no decision authority over the classification itself.

**2. Protecting data in each state**

- **Data at rest** — stored on disk. Protection relies on full-disk encryption, file-level encryption, and physical access control.
- **Data in transit** — crossing the network. Relies on TLS, IPsec, or MACsec for confidentiality and integrity.
- **Data in use** — in the processor or memory, vulnerable to memory scraping and side-channel attacks. Protection relies on confidential computing such as a TEE, plus memory encryption.

**3. Data sanitisation and destruction**

Per NIST SP 800-88, deleting a file does not make the data disappear.

- **Clearing** — overwriting to prevent recovery by ordinary recovery software. Suitable for equipment reused inside the organisation.
- **Purging** — stronger overwriting or degaussing to prevent laboratory-grade recovery. Suitable for equipment released outside the organisation.
- **Destruction** — shredding or melting, offering the highest assurance.
- **Key exam point:** SSDs are not magnetic storage, so **degaussing has absolutely no effect on an SSD**. The only reliable ways to destroy data on an SSD are physical destruction or cryptographic erasure.

### Domain 3 — Security Architecture and Engineering

Roughly 13%. This domain answers the question of how you design security in before the system is built.

**1. Security models**

These determine the direction information may flow.

- **Bell-LaPadula (BLP)** — protects **confidentiality** and prevents leakage. No Read Up, No Write Down.
- **Biba** — protects **integrity** and prevents contamination. The rules are the exact inverse of BLP: No Read Down, No Write Up.
- **Brewer-Nash (Chinese Wall)** — prevents **conflict of interest** through dynamic access control.
- **Clark-Wilson** — ensures data integrity in commercial environments through well-formed transactions and separation of duties.

**2. Cryptography and the post-quantum threat**

**Post-quantum cryptography (PQC)** addresses the *harvest now, decrypt later* threat. Asymmetric encryption such as RSA and ECC is hit hardest by quantum computing; symmetric encryption can be defended simply by doubling key length, such as adopting AES-256. Systems must be designed with **crypto-agility** so algorithms can be swapped smoothly later.

**3. Hardware roots of trust**

- **TPM** — built into the motherboard. Works alongside Secure Boot, handles integrity measurement of the boot process (Measured Boot), and seals local disk encryption keys.
- **HSM** — a standalone tamper-resistant appliance, purpose-built for enterprise-grade, high-performance cryptographic operations and PKI certificate lifecycle management.

### Domain 4 — Communication and Network Security

Roughly 13%, focused on protection across network boundaries and the security challenges of modern distributed networks.

**1. IPsec and encryption modes**

IPsec operates at the network layer (Layer 3), providing secure tunnels between networks.

- **AH vs. ESP** — AH provides integrity but **no confidentiality**, and because its hash covers the outer IP header, **it can never traverse NAT**. ESP provides both confidentiality and integrity, and requires NAT-T (encapsulation in UDP port 4500) in NAT environments.
- **Tunnel Mode** — encrypts the entire original IP packet and adds a new IP header, **completely hiding the internal network addressing structure**. Used for site-to-site VPN.
- **Transport Mode** — encrypts only the payload; the original IP header remains in clear text. Used for end-to-end host communication.

**2. Modern network architecture: SDN and SASE**

- **SDN** — decouples the network control plane (the brain) from the data plane (the limbs). If an attacker injects forged flow entries into a switch, the threat occurs on the **southbound interface** between controller and switch, so the defence must rely on mTLS certificate authentication on that interface.
- **SASE** — converges SD-WAN with SSE (cloud firewall, CASB, ZTNA). Security control moves to globally distributed cloud PoPs, so traffic no longer hairpins back through headquarters. Purpose-built for multi-cloud and remote work architectures.

**3. Wireless security and attack response**

- **WPA3** — uses SAE (Simultaneous Authentication of Equals) to replace the WPA2 PSK handshake. Keys are negotiated dynamically on every connection, providing forward secrecy and eliminating offline dictionary attacks at the root.
- **Rogue AP vs. Evil Twin** — a Rogue AP is an unauthorised device plugged into **your wired network**; the countermeasure is 802.1X port authentication. An Evil Twin impersonates **your SSID** on the wireless side; the root countermeasure is mutual certificate authentication via EAP-TLS.

Building a deep understanding of these four domains and their management perspective lays a solid foundation for access control, security testing, and operations management.

---

## Chapter 5 — Domains 5 to 8 in Depth

These four domains cover the security activities that occur most frequently in daily enterprise operations, and they are where most real-world incidents have concentrated in recent years. On the exam, make sure you think about identity, security testing, incident response, and software development inside the same risk governance framework.

### Domain 5 — Identity and Access Management

13% of the exam, and the largest battlefield in modern security. Perimeter defence has been eroding for years, and attackers no longer hack into systems — **they log in.**

**1. IAM architecture and zero trust**

**Decouple decision from enforcement.** The core of zero trust is separating the **Policy Decision Point (PDP)** from the **Policy Enforcement Point (PEP)**. The PDP centrally computes risk and authorisation; PEPs are distributed across application gateways to intercept and enforce. If a question asks about deployment principles in a distributed architecture: **PDP logically centralised, PEP distributed.**

**The four IAAA layers.** Many candidates lose marks by misclassifying an authorisation problem as an authentication problem.

- **Identification** — who you claim to be, such as an account.
- **Authentication** — proving you are who you claim, such as a password or MFA.
- **Authorisation** — what you are permitted to do, such as RBAC or ACLs. If MFA is already deployed and privilege escalation still occurs, that is a failure of **authorisation**, not of authentication.
- **Accountability** — who did what, via logs and audit. Shared accounts destroy accountability completely.

**2. Modern authentication and threat countermeasures**

**FIDO2 / WebAuthn.** Against adversary-in-the-middle proxy phishing, traditional SMS OTP and push-based MFA both fail. **FIDO2 is currently the only authentication method immune to phishing by design.** Its protection rests on origin binding and the absence of any shared secret on the server side.

**Kerberos and domain threats:**

- **Golden Ticket** — the attacker steals the KRBTGT master key and can forge domain-wide tickets offline, which is equivalent to total domain compromise. The countermeasure requires rotating KRBTGT **twice**.
- **Silver Ticket** — steals a single service account key to forge service tickets. It never touches the KDC, so it leaves no trace in its logs.
- **Kerberoasting** — **any** domain user can request a TGS service ticket and take it away to crack the service account password offline. Countermeasures: enforce AES and retire RC4, or adopt gMSA (group managed service accounts).

**Federation.** SAML produces XML assertions and is used mainly for enterprise web SSO. OAuth handles authorisation only, issuing access tokens. OIDC is built on top of OAuth and handles modern authentication, issuing ID tokens.

**3. Identity lifecycle management**

- **Privileged Access Management (PAM).** Administrative privilege should not be standing. Adopt just-in-time: request when needed, revoke when finished. This is least privilege extended into the time dimension.
- **User Access Review (UAR).** The Mover stage of the joiner/mover/leaver lifecycle is where privilege creep originates. Periodic reviews must be performed by business managers, not by IT staff.

### Domain 6 — Security Assessment and Testing

12% of the exam. The core concept: security cannot merely be claimed. It must be independently verified.

**1. Audit and third-party assurance**

- **Audit independence.** Whoever built a control absolutely cannot audit their own work.
- **SOC 2 reports.** A standard exam item when assessing cloud vendors. **Type I** evaluates only design suitability at a single point in time. **Type II** evaluates design *and operating effectiveness* over a period, typically 6 to 12 months. To prove a control has been continuously effective, you need Type II.

**2. Penetration testing and vulnerability management**

- **Written authorisation is an absolute prerequisite.** Explicit written authorisation and rules of engagement must be obtained before testing; without them it is legally indistinguishable from unlawful intrusion. The tester may never expand the scope unilaterally.
- **Vulnerability prioritisation.** Don't rely on the CVSS score alone — that measures inherent severity. The best answer in practice and on the exam is to prioritise **CISA KEV** (vulnerabilities confirmed as exploited in the wild), followed by those with high **EPSS** (high probability of exploitation) that are exposed to the internet.

**3. Comparing application testing tools**

- **SAST** — reviews source code during development. High coverage and early detection, but a high false positive rate and no visibility into the runtime environment.
- **DAST** — black-box testing against a running application. Low false positives and close to real attacks, but cannot point to a specific line of code.
- **Mutation testing** — deliberately injects small defects into source code to verify the quality and coverage of the **test cases themselves**.

### Domain 7 — Security Operations

13% of the exam, covering the daily firefighting and maintenance work of an enterprise.

**1. Incident response lifecycle**

- **Containment first.** Per NIST SP 800-61, once an incident is identified, containment (stopping the bleeding) always precedes eradication (cleaning up) and recovery. Rushing to rebuild a system destroys evidence and leads to expanded losses or reinfection.
- **Digital forensics and the order of volatility.** Evidence must be collected starting with the most volatile: CPU registers → RAM → network connections → disk. This is exactly why "immediately pull the power" is usually the wrong answer when malware is involved — it destroys the critical evidence held in memory. And once the chain of custody is broken, the evidence becomes inadmissible in court.

**2. Backup and disaster recovery**

- **Backup mechanisms.** Incremental backup captures changes since the last backup *of any kind* and is the slowest to restore; differential backup captures changes since the last *full* backup. The baseline defence against ransomware is **immutable backup (WORM)**.
- **DR testing.** From lightest to heaviest: Read-through → Tabletop → Simulation → Parallel → **Full Interruption**. Full interruption carries the highest risk, requires approval at the most senior level, and the exercise programme must progress through the levels in order — you cannot jump straight to the top.

**3. Change and personnel controls**

- **Change management.** Most service outages originate from your own bad configuration pushes. Every change **must include a rollback plan**. Emergency changes may be approved retroactively, but the record may never be skipped.
- **Personnel detective controls.** Job rotation and mandatory vacation exist primarily to **detect fraud**, by letting whoever takes over notice the anomaly — not for prevention, and not for cross-training.

### Domain 8 — Software Development Security

10% of the exam, exploring how to eliminate vulnerabilities at the source.

**1. Shift-left and maturity models**

Security must be considered at the requirements and design stages. Fixing a flaw at the requirements stage costs almost nothing; leaving it until production means an exponentially higher cost.

**SAMM vs. BSIMM.** OWASP SAMM is a **prescriptive** model that tells you what you should be doing. BSIMM is a **descriptive** model that measures and reports what other organisations in the industry actually do.

**2. Core vulnerabilities and defences**

- **XSS.** The attacker injects a script that executes in the user's browser and steals the session token. **The most fundamental countermeasure is output encoding**, not input filtering alone.
- **SQL injection.** The fundamental defence is **parameterised queries / prepared statements**, which completely separate code from user-supplied data.
- **CSRF.** Induces the victim's browser to send an unintended request. Defence relies on the synchroniser token pattern or SameSite cookies. Note: CSP defends against XSS, not CSRF.
- **SSRF.** Tricks the server into reaching internal resources, for example stealing the cloud environment's IAM instance credentials. Defences include IMDSv2, egress allow-lists, and blocking internal reserved ranges.

**3. Software supply chain and database protection**

- **SBOM.** Essential documentation in a modern open-source ecosystem. When a major vulnerability such as Log4j breaks, an SBOM lets an organisation determine exposure within hours instead of spending weeks on inventory.
- **Database ACID properties.** Atomicity (never half-done), Consistency (never invalid), Isolation (prevents concurrent interference, and is what prevents TOC/TOU race conditions), Durability (survives a crash).

---

## Closing

Preparing for the CISSP is really a journey of reshaping how you think about security. Once you hold the certification and return to your organisation, your value is no longer just configuring systems — it is being able to put a sharp, uncomfortable management question to the board and to the business. (It also gives you a good excuse to clear out some ageing technical and management assumptions along the way.)

So when you finally walk into the CISSP exam room, bring the confidence of a CISO, the composure of an external consultant, and an absolute commitment to protecting human life. Everything you have built over these months will turn into something sweet the moment you click submit.

Good luck.

---

## References and Links

**Official**

- [CISSP Certification Exam Outline — ISC2](https://www.isc2.org/certifications/cissp/cissp-certification-exam-outline)

**Study Resources**

- [lorenzoleonelli/CISSP-Zero-to-Hero](https://github.com/lorenzoleonelli/CISSP-Zero-to-Hero) — my primary material; actively maintained, covers AI and PQC
- [KinofRikin/CisspStudy](https://github.com/KinofRikin/CisspStudy)
- [firmianay CISSP Notes](https://firmianay.gitbook.io/cissp-notes)
- [connectans/awesome-CISSP-CCSP](https://github.com/connectans/awesome-CISSP-CCSP)
- [leec94/cissp-notes](https://github.com/leec94/cissp-notes/)
- [ethanolivertroy/cissp-examprep-2023](https://github.com/ethanolivertroy/cissp-examprep-2023/)
- [pzerger/cisspexamcram](https://github.com/pzerger/cisspexamcram/) — companion repo to the Exam Cram video series
- [jefferywmoore/CISSP-Study-Resources](https://github.com/jefferywmoore/CISSP-Study-Resources)
- [OpenSecurityTraining — CISSP](https://opensecuritytraining.info/CISSP-Main.html)

**Community Write-ups**

- [hackmd.io/@hpsh31323](https://hackmd.io/@hpsh31323/rk3mgXD7p)
- [hackmd.io/@TTC989](https://hackmd.io/@TTC989/BkA8CRx6s)
- [Passing the CISSP in 20 days — Medium](https://raylin-ai-pm.medium.com/%E7%9B%AE%E6%A8%99%E5%B0%8E%E5%90%91-20%E5%A4%A9%E5%85%89%E9%80%9F%E8%80%83%E9%81%8Ecissp-f0f6f686117b)

**Threat Landscape and Standards**

- [MITRE ATLAS — Case Studies](https://atlas.mitre.org/studies) and [Matrix](https://atlas.mitre.org/matrices/ATLAS-matrix) — adversarial threat landscape for AI systems
- [MITRE ATT&CK](https://attack.mitre.org/)
- [AI Incident Database](https://incidentdatabase.ai/summaries/incidents/)
- OWASP Top Ten (2025)
- OWASP GenAI / LLM Top 10 (2026 v1.0)
- CWE — latest list
- NIST SP 800 series
- European Parliament Research Service briefing EPRS_BRI(2021)698792 — EU cybersecurity policy background

---

