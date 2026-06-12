# Healthcare AI Theme/Sub-theme Taxonomy

## Labeling Rule

For each post, assign the most relevant concern as the Primary Theme and Primary Sub_Theme. If the post contains an additional clearly expressed concern, record it in separate fields/column labeled Secondary Theme and Secondary Sub_Theme. Secondary labels should only be assigned when the concern is explicit or strongly implied, and each label must be supported by evidence from the title, selftext, or top_comments.

---

## Theme 1: Data Collection

**Definition:** Posts discussing what information is collected from users, patients, clinicians, or healthcare systems by AI-enabled technologies.

**Include:**
- Collection of personal information
- Tracking user interactions
- Monitoring patient activities
- Gathering health records
- Wearable-generated data
- Chat logs and prompts

**Exclude:**
- How collected data is later used
- Data sharing with external parties
- Security incidents after collection

### Subtheme 1.1: Personally Identifiable Information (PII)

**Definition:** Discussions about collection or handling of information that can directly or indirectly identify an individual.

**Include:**
- Name
- Address
- Email
- Phone number
- Medical record number
- Patient identifiers
- Genetic information tied to an individual

**Example:** “The chatbot asked for my medical record number.”

**Exclude:**
- Anonymous aggregate data
- Behavioral logs without identifiable information

### Subtheme 1.2: Activity and Behavioral Data

**Definition:** Discussions about collection of user activities, interactions, habits, monitoring data, or behavioral patterns.

**Include:**
- Conversation logs
- Search history
- Wearable device tracking
- Patient monitoring
- Usage analytics
- Clickstream data
- Symptom tracking

**Example:** “The app records every symptom I enter.”

**Exclude:**
- Training of models using the collected data
- Data sharing with third parties

---

## Theme 2: Data Usage

**Definition:** Posts discussing how collected healthcare data is utilized after collection.

**Include:**
- AI development or training
- Research use
- Commercial use
- Data monetization
- External sharing

**Exclude:**
- Initial data collection
- Storage duration
- Security breaches

### Subtheme 2.1: Model Training

**Definition:** Discussions about healthcare data being used to train, fine-tune, evaluate, or improve AI systems.

**Include:**
- ChatGPT training
- LLM fine-tuning
- Medical chatbot development
- Speech transcription training
- Dataset construction
- AI model improvement

**Example:** “Are patient conversations used to train the chatbot?”

**Exclude:**
- Sharing data with outside organizations
- General AI performance discussions

### Subtheme 2.2: Third-Party Sharing

**Definition:** Discussions regarding healthcare data being shared, sold, licensed, transferred, or accessed by external organizations.

**Include:**
- Vendors
- Insurance companies
- Advertisers
- Cloud providers
- Business partners
- Data brokers
- Sharing, selling, transferring, disclosing, or external access

**Example:** “The hospital shares patient information with a technology company.”

**Exclude:**
- Internal use within the same organization
- Model training conducted solely by the data owner

---

## Theme 3: Data Retention

**Definition:** Posts discussing storage duration, retention policies, deletion, archiving, or long-term preservation of healthcare data.

**Include:**
- Data deletion
- Data retention policies
- Long-term storage
- Permanent records
- Right to be forgotten

**Example:** “How long does the AI system keep my medical conversations?”

**Exclude:**
- Data collection
- Data sharing
- Security breaches

---

## Theme 4: Security Vulnerabilities

**Definition:** Posts discussing technical weaknesses, attacks, exploits, or security risks affecting medical AI systems or healthcare infrastructure.

**Include:**
- Cyberattacks
- Unauthorized access
- Security flaws
- Compromised systems
- Prompt injection
- Safety bypass
- RAG or memory poisoning
- Malicious automation
- Workflow misuse

**Exclude:**
- Privacy concerns without security implications
- Regulatory discussions
- Safety, bias, or trust concerns without security implications

### Subtheme 4.1: Platform Security

**Definition:** Technical attacks or failures that compromise system confidentiality, integrity, or availability.

**Include:**
- Data breaches
- Ransomware
- Hacking incidents
- Unauthorized access
- Firewall failures
- Cloud security failures
- Credential theft
- Security misconfigurations

**Example:** “The hospital's AI platform was hacked and patient records were exposed.”

**Exclude:**
- AI-generated incorrect diagnoses
- Bias
- Regulatory compliance

### Subtheme 4.2: AI Agents and Workflow Security

**Definition:** Security or abuse concerns arising from AI agents, autonomous systems, RAG systems, memory-enabled AI systems, or AI-integrated healthcare workflows.

**Include:**
- Prompt injection
- Safety bypass
- Jailbreaks
- RAG poisoning
- Memory poisoning
- Tool misuse
- Malicious automation
- Workflow misuse
- Agentic AI abuse
- Unauthorized autonomous actions
- AI assistants taking unsafe or unintended actions
- Security risks from clinical workflow automation

**Example:** “A malicious prompt caused the AI agent to approve a patient referral without authorization.”

**Exclude:**
- Traditional data breaches
- General model training discussions
- Human oversight concerns without a security or abuse component

---

## Theme 5: Regulatory & Legal Compliance

**Definition:** Posts discussing legal, ethical, or regulatory obligations governing healthcare data and AI systems.

**Include:**
- Regulatory compliance
- Privacy laws
- Healthcare regulations
- Legal obligations
- Certification or approval requirements

**Exclude:**
- Technical security incidents
- General trust concerns
- Clinical safety concerns without regulatory context

### Subtheme 5.1: HIPAA

**Definition:** Discussions explicitly involving HIPAA compliance, violations, or handling of Protected Health Information (PHI).

**Include:**
- HIPAA violations
- PHI exposure
- HIPAA compliance questions
- HIPAA audits
- Protected patient information

**Example:** “Is ChatGPT HIPAA compliant?”

**Exclude:**
- General privacy concerns that do not mention healthcare regulations

### Subtheme 5.2: FDA

**Definition:** Discussions involving FDA oversight, approval, regulation, certification, or governance of medical AI systems.

**Include:**
- FDA approval
- Software as Medical Device (SaMD)
- FDA guidance
- Medical device regulation
- Clinical validation requirements

**Example:** “Has this AI diagnostic system received FDA approval?”

**Exclude:**
- HIPAA discussions
- General safety concerns without regulatory context

### Subtheme 5.3: EU Regulatory Compliance

**Definition:** Discussions involving European healthcare AI regulations, GDPR, the EU AI Act, MDR, CE marking, European data protection requirements, or cross-border European healthcare data governance.

**Include:**
- GDPR
- EU AI Act
- EU Medical Device Regulation (MDR)
- CE marking
- European health data regulation
- European data residency
- Cross-border healthcare data transfer
- EU compliance requirements

**Example:** “Can an AI medical chatbot process patient data under GDPR and the EU AI Act?”

**Exclude:**
- HIPAA-specific discussions
- FDA-specific discussions
- General privacy concerns without European regulatory context

---

## Theme 6: Trust & Responsible AI

**Definition:** Posts discussing whether medical AI systems are reliable, fair, responsible, transparent, explainable, accountable, or deserving of user trust.

**Include:**
- Reliability
- Fairness
- Accountability
- Explainability
- Transparency
- Human oversight
- Trustworthiness
- Clinical responsibility

**Exclude:**
- Technical security vulnerabilities
- Data collection practices
- Regulatory compliance unless explicitly legal/regulatory

### Subtheme 6.1: Safety

**Definition:** Discussions that medical AI may cause harm through incorrect, unsafe, unreliable, or misleading outputs.

**Include:**
- Misdiagnosis
- Hallucinations
- Unsafe recommendations
- Incorrect treatment suggestions
- Automation bias
- Clinical reliability

**Example:** “The AI recommended the wrong medication.”

**Exclude:**
- Security breaches
- Bias and discrimination concerns

### Subtheme 6.2: Bias

**Definition:** Discussions that AI systems produce unfair, discriminatory, or systematically unequal outcomes across populations.

**Include:**
- Racial bias
- Gender bias
- Age bias
- Dataset bias
- Fairness concerns
- Unequal healthcare outcomes

**Example:** “The model performs worse for minority patients.”

**Exclude:**
- General safety concerns
- Privacy concerns

### Subtheme 6.3: Explainability

**Definition:** Discussions that medical AI systems do not provide understandable, transparent, or interpretable reasons for their outputs.

**Include:**
- Lack of explanation
- Black-box decisions
- Unclear reasoning
- Poor transparency
- Difficulty interpreting model recommendations
- Need for understandable clinical rationale

**Example:** “The AI gave a diagnosis but did not explain why.”

**Exclude:**
- Incorrect or unsafe recommendations, unless the concern is specifically about lack of explanation
- Regulatory approval questions

### Subtheme 6.4: Human Oversight

**Definition:** Discussions about whether humans, clinicians, patients, or institutions can supervise, contest, override, or remain accountable for AI-assisted healthcare decisions.

**Include:**
- Clinician-in-the-loop
- Human review
- Accountability for AI decisions
- Ability to override AI outputs
- Overreliance on automation
- Responsibility when AI causes harm
- Autonomous clinical decisions without review

**Example:** “A doctor should review the AI recommendation before it affects patient care.”

**Exclude:**
- Security-focused autonomous misuse
- Prompt injection, RAG poisoning, or malicious workflow abuse


OUTPUT_FORMAT = """
OUTPUT — return ONLY valid JSON, no markdown fences:
{
  "Primary_Theme": "<most relevant theme from the allowed list>",
  "Primary_Sub_Theme": "<most relevant sub-theme from the allowed list>",
  "Primary_Evidence_Span": "<short evidence span from title, selftext, or top_comments>",
  "Secondary_Theme": "<second relevant theme from the allowed list, or None>",
  "Secondary_Sub_Theme": "<second relevant sub-theme from the allowed list, or None>",
  "Secondary_Evidence_Span": "<short evidence span from title, selftext, or top_comments, or None>",
  "Annotation_Notes": "<1-3 sentence justification>"
}
"""