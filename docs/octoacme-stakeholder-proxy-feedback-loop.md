# Stakeholder Proxy Feedback Loop

## Purpose
This document defines how Stakeholder Proxies facilitate rapid feedback and decision-making between delivery teams and broader stakeholder groups. It ensures teams get timely input without overwhelming all stakeholders with every detail.

## The Stakeholder Proxy Role
A Stakeholder Proxy is empowered to make delegated decisions on behalf of a broader stakeholder group, providing rapid feedback to unblock team progress while maintaining appropriate governance and transparency.

---

## Feedback Loop Process

### 1. Request Initiation
When the team needs stakeholder input, they:
- [ ] Clearly articulate the decision or feedback needed
- [ ] Provide relevant context (why now, what are we trying to achieve)
- [ ] Include any constraints or trade-offs
- [ ] Specify desired response timeline (e.g., 24 hours, 3 days)
- [ ] Indicate whether this is delegated decision or needs full stakeholder review

### 2. Proxy Assessment
The Stakeholder Proxy evaluates:
- [ ] Is this within my delegated authority?
- [ ] Do I have enough context to respond?
- [ ] Are there hidden implications I need to surface?
- [ ] Should I consult specific stakeholders before responding?

### 3. Response Options

#### Option A: Direct Response (Delegated Authority)
- [ ] Proxy provides feedback or approval within agreed timeline
- [ ] Documents decision and rationale in project log
- [ ] Includes any conditions or follow-up items
- [ ] Informs broader stakeholder group in next regular update

#### Option B: Escalation (Needs Broader Input)
- [ ] Proxy identifies why escalation is needed
- [ ] Brings request to stakeholder group with recommendation
- [ ] Facilitates stakeholder discussion and decision
- [ ] Communicates decision back to team with context
- [ ] Updates delegation boundaries if pattern emerges

#### Option C: Clarification Needed
- [ ] Proxy requests additional information from team
- [ ] Team provides clarification
- [ ] Loop back to step 2

### 4. Team Acknowledgment
- [ ] Team acknowledges receipt of feedback
- [ ] Confirms understanding of any conditions or caveats
- [ ] Updates plan based on stakeholder input
- [ ] Flags any concerns or implementation challenges

### 5. Validation and Closure
- [ ] Proxy validates team's implementation of feedback
- [ ] Confirms outcome meets stakeholder expectations
- [ ] Documents lessons learned for future requests
- [ ] Closes feedback loop

---

## Delegation Framework

### What Stakeholder Proxies Can Typically Decide

**Low-Risk, Delegated Authority:**
- Minor scope clarifications within approved budget/timeline
- UI/UX refinements that don't change core functionality
- Content and messaging adjustments
- Non-critical timeline adjustments (1-2 days)
- Tactical prioritization within a sprint
- Go-ahead on low-risk experiments or prototypes

**Examples:**
- "Can we adjust button placement based on usability testing?"
- "Should we prioritize bug fix A or B in this sprint?"
- "Can we extend testing by 2 days to improve quality?"

### What Requires Full Stakeholder Review

**High-Risk, Needs Escalation:**
- Changes to core project scope or deliverables
- Budget increases or resource requests
- Timeline extensions beyond agreed tolerance (e.g., >1 week)
- Decisions with legal, security, or compliance implications
- Changes that affect other teams or dependencies
- Strategic pivots or significant trade-offs

**Examples:**
- "We need to cut Feature X to meet timeline—is that acceptable?"
- "Implementing this will require 3 additional weeks and $50K budget"
- "We discovered a compliance issue that changes our approach"

---

## Communication Templates

### Template: Feedback Request to Stakeholder Proxy

```
**Decision/Feedback Needed:**
[Clear, specific question or decision]

**Context:**
[Why this matters, what problem we're solving]

**Options Considered:**
1. [Option A with pros/cons]
2. [Option B with pros/cons]

**Team Recommendation:**
[What the team recommends and why]

**Impact of Delay:**
[What happens if we don't decide quickly]

**Response Needed By:**
[Date/time]

**Questions for Proxy:**
[Any specific aspects where stakeholder perspective is critical]
```

### Template: Proxy Response to Team

```
**Decision:**
[Approve / Approve with conditions / Decline / Escalating to stakeholders]

**Rationale:**
[Why this decision was made, key considerations]

**Conditions (if any):**
[Any constraints or requirements]

**Next Steps:**
[What team should do next]

**Follow-up:**
[When/how proxy will validate outcome]
```

### Template: Proxy Update to Stakeholder Group

```
**Decisions Made This Week (Delegated Authority):**
- [Decision 1]: [Brief context and outcome]
- [Decision 2]: [Brief context and outcome]

**Issues Escalated for Stakeholder Input:**
- [Issue 1]: [Context and recommendation]

**Upcoming Decisions:**
- [Decision 1]: [When feedback will be needed]

**Concerns or Trends:**
[Any patterns stakeholders should be aware of]
```

---

## Feedback Loop SLAs

### Standard Response Times
- **Routine feedback**: 2-3 business days
- **Urgent feedback**: 24 hours
- **Critical blocker**: Same day (4 hours)

### Escalation Response Times
- **Stakeholder review needed**: 3-5 business days
- **Urgent stakeholder review**: 2 business days
- **Emergency stakeholder review**: 24 hours

*Note: Set expectations with team and stakeholders on what constitutes "urgent" vs "routine"*

---

## Metrics and Health Indicators

### Effective Feedback Loop
- ✅ 90%+ of requests answered within SLA
- ✅ <20% escalation rate (most handled via delegation)
- ✅ Clear decision rationale provided
- ✅ Team reports satisfaction with feedback quality and speed
- ✅ No surprises for stakeholders at formal reviews

### Warning Signs
- ⚠️ Frequent missed SLAs or delayed responses
- ⚠️ >50% escalation rate (delegation boundaries unclear)
- ⚠️ Repeated questions on same topics (documentation gap)
- ⚠️ Stakeholders surprised by decisions made via proxy
- ⚠️ Team bypassing proxy to go directly to stakeholders

---

## Continuous Improvement

### Quarterly Review
- [ ] Review delegation boundaries—are they right-sized?
- [ ] Analyze escalation patterns—can we clarify more?
- [ ] Gather feedback from team on proxy effectiveness
- [ ] Gather feedback from stakeholders on communication quality
- [ ] Update delegation framework based on learnings

### Common Adjustments
- **Expand delegation**: If proxy consistently escalates low-risk items
- **Narrow delegation**: If stakeholders are surprised by decisions
- **Improve documentation**: If same questions arise repeatedly
- **Adjust SLAs**: If current timelines don't match team needs
- **Change proxy**: If person is overwhelmed or lacks necessary context

---

## Example Scenarios

### Scenario 1: Feature Refinement (Delegated)
**Request**: "User testing shows our form is confusing. Can we add help text and reorganize fields?"
**Proxy Response**: "Approved. This is a usability improvement within scope. Ensure help text is reviewed for clarity before shipping."
**Outcome**: Team implements changes, proxy validates in demo, stakeholders informed in weekly update.

### Scenario 2: Scope Change (Escalated)
**Request**: "Implementing Feature X as specified will delay us 3 weeks. Can we descope to a simpler version?"
**Proxy Response**: "This is a significant trade-off. I'm escalating to stakeholders with recommendation to approve simplified version. Need decision by Friday."
**Outcome**: Stakeholders review options, approve simplified version with plan to add full version in future release.

### Scenario 3: Technical Decision (Delegated with Conditions)
**Request**: "Should we use Library A (familiar but older) or Library B (modern but learning curve)?"
**Proxy Response**: "Approved to use Library B with condition: Tech Lead must document knowledge transfer plan and training timeline."
**Outcome**: Team proceeds with Library B, creates training materials, proxy validates plan before full implementation.

---

## Getting Started

### For New Stakeholder Proxies
1. Review this document with PM and PdM
2. Meet with stakeholder group to clarify delegation boundaries
3. Shadow another proxy if possible
4. Start with conservative delegation and expand based on experience
5. Over-communicate initially until rhythm is established

### For Teams Working with a New Proxy
1. Clarify delegation boundaries in kickoff meeting
2. Start with small, low-risk requests to build trust
3. Provide thorough context in early requests
4. Give feedback on response quality and timing
5. Be patient as proxy learns the project domain

---

*Related to issue #4 - Added to clarify stakeholder proxy role and improve decision-making speed*
