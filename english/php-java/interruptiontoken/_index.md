---
title: InterruptionToken
type: docs
weight: 0
url: /php-java/interruptiontoken/
---

# InterruptionToken class

 This class represents the token to use for signaling long running tasks whether the interruption was requested.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getNone](/php-java/interruptiontoken/getnone/)() | InterruptionToken | Represents an empty interruption token. Long-running operations will never be interrupted via InterruptionTokenSource#interrupt when using this token. |
| [isInterruptionRequested](/php-java/interruptiontoken/isinterruptionrequested/)() | boolean | Returns true if interruption was requested. |
| [throwIfInterruptionRequested](/php-java/interruptiontoken/throwifinterruptionrequested/)() | void | Throws an if interruption was requested. |
