# Autonomous Investigation Agent

This module will coordinate the investigation workflow after suspicious transaction activity is detected.

## Planned Responsibilities

- Receive high-risk transaction alerts
- Retrieve relevant transaction and wallet information
- Expand connected transaction graphs
- Identify related entities and behavioral patterns
- Correlate available threat intelligence
- Request additional intelligence when required
- Calculate evidence-backed risk assessments
- Generate investigation summaries and reports

## Planned Investigation Flow

**Alert**
→ **Collect Evidence**
→ **Expand Graph**
→ **Correlate Intelligence**
→ **Assess Risk**
→ **Explain Findings**
→ **Prioritize Investigation**

## Planned Agent Tools

The agent may interact with specialized tools such as:

- `get_transactions()`
- `get_wallet_features()`
- `expand_graph()`
- `find_clusters()`
- `calculate_risk()`
- `generate_report()`

## Future x402 Integration

The agent is planned to interact with x402-enabled intelligence services.

When additional specialized intelligence is required, the agent can request the service and, in the final implementation, programmatically make an x402 payment using Algorand before receiving the requested intelligence.

## Status

**Planned — MVP development**
