# Overview for Diagram **StandardInbound**:

![Diagram StandardInbound](../png/StandardInbound.png)
## recognized shapes from b.telligent Shape Library:

|Shape ID|Shape Type|Label|
|--------|----------|-----|
|StandardInbound.tnuW1UExQAtQYmTLPYoE-152|Satellite|default|
|StandardInbound.tnuW1UExQAtQYmTLPYoE-160|Hub|Location|
|StandardInbound.tnuW1UExQAtQYmTLPYoE-170|Satellite|default|
|StandardInbound.tnuW1UExQAtQYmTLPYoE-178|Hub|Client|
|StandardInbound.tnuW1UExQAtQYmTLPYoE-188|Link|Link|
|StandardInbound.tnuW1UExQAtQYmTLPYoE-195|Satellite|default|
|StandardInbound.tnuW1UExQAtQYmTLPYoE-203|Hub|Advice|
|StandardInbound.tnuW1UExQAtQYmTLPYoE-215|Satellite|default|
|StandardInbound.tnuW1UExQAtQYmTLPYoE-223|Hub|Advice Line|
|StandardInbound.tnuW1UExQAtQYmTLPYoE-233|Link|Link|
|StandardInbound.tnuW1UExQAtQYmTLPYoE-242|Satellite|default|
|StandardInbound.tnuW1UExQAtQYmTLPYoE-250|Hub|Article|
|StandardInbound.tnuW1UExQAtQYmTLPYoE-260|Link|Link|
|StandardInbound.tnuW1UExQAtQYmTLPYoE-269|Satellite|Process Status|
|StandardInbound.tnuW1UExQAtQYmTLPYoE-278|Satellite|Process Status|
|StandardInbound.tnuW1UExQAtQYmTLPYoE-287|Reference|Process Status|
|StandardInbound.tnuW1UExQAtQYmTLPYoE-302|Comment|Hier gibt es noch eine Menge Kommentare!|

## recognized connections from b.telligent Shape Library:

|Source Type|Source Label|Connection Type|Label|Target Type|Target Label|Connection ID|Source ID|Target ID|
|-----------|------------|---------------|-----|-----------|------------|-------------|---------|---------|
|Satellite|default|Sat-to-Hub||Hub|Location|StandardInbound.tnuW1UExQAtQYmTLPYoE-169|StandardInbound.tnuW1UExQAtQYmTLPYoE-152|StandardInbound.tnuW1UExQAtQYmTLPYoE-160
|Satellite|default|Sat-to-Hub||Hub|Client|StandardInbound.tnuW1UExQAtQYmTLPYoE-187|StandardInbound.tnuW1UExQAtQYmTLPYoE-170|StandardInbound.tnuW1UExQAtQYmTLPYoE-178
|Satellite|default|Sat-to-Hub||Hub|Advice|StandardInbound.tnuW1UExQAtQYmTLPYoE-212|StandardInbound.tnuW1UExQAtQYmTLPYoE-195|StandardInbound.tnuW1UExQAtQYmTLPYoE-203
|Satellite|default|Sat-to-Hub||Hub|Advice Line|StandardInbound.tnuW1UExQAtQYmTLPYoE-232|StandardInbound.tnuW1UExQAtQYmTLPYoE-215|StandardInbound.tnuW1UExQAtQYmTLPYoE-223
|Satellite|default|Sat-to-Hub||Hub|Article|StandardInbound.tnuW1UExQAtQYmTLPYoE-259|StandardInbound.tnuW1UExQAtQYmTLPYoE-242|StandardInbound.tnuW1UExQAtQYmTLPYoE-250
|Satellite|Process Status|Sat-to-Hub||Hub|Advice|StandardInbound.tnuW1UExQAtQYmTLPYoE-277|StandardInbound.tnuW1UExQAtQYmTLPYoE-269|StandardInbound.tnuW1UExQAtQYmTLPYoE-203
|Satellite|Process Status|Sat-to-Hub||Hub|Advice Line|StandardInbound.tnuW1UExQAtQYmTLPYoE-286|StandardInbound.tnuW1UExQAtQYmTLPYoE-278|StandardInbound.tnuW1UExQAtQYmTLPYoE-223
|Reference|Process Status|Sat-to-Hub||Satellite|Process Status|StandardInbound.tnuW1UExQAtQYmTLPYoE-299|StandardInbound.tnuW1UExQAtQYmTLPYoE-287|StandardInbound.tnuW1UExQAtQYmTLPYoE-269
|Reference|Process Status|Sat-to-Hub||Satellite|Process Status|StandardInbound.tnuW1UExQAtQYmTLPYoE-300|StandardInbound.tnuW1UExQAtQYmTLPYoE-287|StandardInbound.tnuW1UExQAtQYmTLPYoE-278
|Hub|Advice|Hub-to-Link-1||Link|Link|StandardInbound.tnuW1UExQAtQYmTLPYoE-213|StandardInbound.tnuW1UExQAtQYmTLPYoE-203|StandardInbound.tnuW1UExQAtQYmTLPYoE-188
|Hub|Client|Hub-to-Link-N||Link|Link|StandardInbound.tnuW1UExQAtQYmTLPYoE-214|StandardInbound.tnuW1UExQAtQYmTLPYoE-178|StandardInbound.tnuW1UExQAtQYmTLPYoE-188
|Hub|Advice|Hub-to-Link-N||Link|Link|StandardInbound.tnuW1UExQAtQYmTLPYoE-240|StandardInbound.tnuW1UExQAtQYmTLPYoE-203|StandardInbound.tnuW1UExQAtQYmTLPYoE-233
|Hub|Advice Line|Hub-to-Link-1||Link|Link|StandardInbound.tnuW1UExQAtQYmTLPYoE-241|StandardInbound.tnuW1UExQAtQYmTLPYoE-223|StandardInbound.tnuW1UExQAtQYmTLPYoE-233
|Hub|Advice Line|Hub-to-Link-1||Link|Link|StandardInbound.tnuW1UExQAtQYmTLPYoE-267|StandardInbound.tnuW1UExQAtQYmTLPYoE-223|StandardInbound.tnuW1UExQAtQYmTLPYoE-260
|Hub|Article|Hub-to-Link-N||Link|Link|StandardInbound.tnuW1UExQAtQYmTLPYoE-268|StandardInbound.tnuW1UExQAtQYmTLPYoE-250|StandardInbound.tnuW1UExQAtQYmTLPYoE-260
|Hub|Location|Hub-to-Link-N||Link|Link|StandardInbound.tnuW1UExQAtQYmTLPYoE-301|StandardInbound.tnuW1UExQAtQYmTLPYoE-160|StandardInbound.tnuW1UExQAtQYmTLPYoE-188
