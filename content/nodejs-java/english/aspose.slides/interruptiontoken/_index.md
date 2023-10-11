---
title: InterruptionToken
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/interruptiontoken/
---

## InterruptionToken class

 This class represents the token to use for signaling long running tasks whether the interruption was requested.
 
| [getNone] () Represents an empty interruption token. Long-running operations will never be interrupted via InterruptionTokenSource#interrupt when using this token. |

### Result
InterruptionToken


---


| [isInterruptionRequested] () Returns true if interruption was requested. |

### Result
boolean


---


| [throwIfInterruptionRequested] () Throws an if interruption was requested. |

### Error

| Error | Condition |
| --- | --- |
 | OperationCanceledException | Thrown when interruption was requested. |


---


