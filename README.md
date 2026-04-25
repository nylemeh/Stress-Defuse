# 🌿 Project Report — *Stress Defuse QA Team*

> *A collaborative deep dive into testing, teamwork, and tiny bugs with big lessons.*

---

## 🧩 Our Approach

✨ **How we made it work:**
- 🗣️ Team communication flowed through **Discord**
- 🗓️ First team meeting: mapped out a **project plan + testing timeline**
- ⚙️ Divided and conquered: each tester owned specific modules
- ⏰ Worked **asynchronously** with nightly check-ins
- 🤝 Reunited for collaborative reviews and cohesive final reports  

> In short: daily accountability, open feedback, and a whole lot of caffeine.

---

## 🧪 Methodologies Used

We approached this project with a full-spectrum testing mindset — covering functionality, performance, and accessibility from every angle.

| Type of Testing | Total Tests | % of Total |
|------------------|--------------|-------------|
| 🧠 Functional | 75 | 28% |
| ⚙️ Non-Functional | 63 | 24% |
| ♿ Accessibility | 9 | 3% |
| 🚀 Performance | 16 | 6% |
| 💻 Compatibility | 104 | 39% |
| **Total** | **267** | **100%** |

---

### 📊 Test Results Summary

> **100% coverage** achieved 🎯  

| Status | Tests | % |
|---------|--------|---|
| ✅ Passed | 184 | 68.91% |
| ❌ Failed | 83 | 31.09% |

---

### 🐞 Bug Findings & Priorities

| Priority | Count |
|-----------|--------|
| 🔥 **Highest** | 24 |
| 🚨 High | 5 |
| ⚖️ Medium | 26 |
| 🧩 Low | 25 |
| 💤 Lowest | 3 |
| **Total Bugs** | **83** |

---

### 📉 Failure Distribution by Category

| Category | Failed | Failure Rate |
|-----------|---------|---------------|
| 🧠 Functional | 31 | 37.3% |
| ⚙️ Non-Functional | 13 | 15.7% |
| 🚀 Performance | 8 | 9.6% |
| ♿ Accessibility | 3 | 3.6% |
| 💻 Compatibility | 28 | 33.7% |

---

## 💥 Major Bug Findings

| Bug ID | Description | Impact | Category |
|--------|--------------|---------|-----------|
| **SDA_15 & SDA_16** | Reset Behavior fails to trigger daily at 00:00 EST; resets every 2–3 days instead | 🟥 Highest Priority | Functionality |
| **SDA_17** | No badges displayed in the *“Here are your badges!”* section post-challenge | 🟥 Highest Priority | Functionality |
| **SDA_21 & SDA_23** | Field validation missing in *Build Your Routine* and *Reminders* | 🟧 High Priority | Functionality |

> 🔎 These bugs directly impact user engagement and challenge progression, significantly reducing usability.

---

## 🧭 Application State Assessment

Based on the requirements document, several **core features** are **non-functional** — resulting in major usability challenges. 
Two primary functions fail to meet the defined requirements.

💡 **Team Conclusion:**  
> The current build is *not yet production-ready* and requires significant refinement before release.

---

## 🧰 Tools & Environments

### 💻 Environments Tested
- Google Chrome  
- Mozilla Firefox  
- Microsoft Edge  
- Apple Safari  

### 🧪 Tools Used
| Tool | Purpose |
|------|----------|
| 🧭 **DevTools** | Environment control & live debugging |
| 🐞 **Jira** | Bug reporting & tracking |
| 📊 **Google Sheets** | Test case documentation |
| 🌈 **Lighthouse** | Accessibility audits |
| 🧾 **Google Slides** | Test analysis presentation |
| 🎥 **Zoom** | Team meetings & recordings |

---

## 🧑‍🤝‍🧑 Team Allocations

| Team Member | Focus Areas |
|--------------|--------------|
| **Young Hui** | Daily Challenges, CalmCorner, Performance/Accessibility |
| **Nyleme Herrera** | CozyClock & Routine Reminders|
| **Richa Kumar** | Daily Challenges, CalmCorner |

---

## 🌟 Final Reflections

We built a testing process grounded in **team trust, clear documentation, and continuous feedback**.  
Every bug became a learning moment, and every pass reminded us that quality is a shared victory.

> “In QA, progress isn’t about perfection — it’s about persistence.” 🕊️
