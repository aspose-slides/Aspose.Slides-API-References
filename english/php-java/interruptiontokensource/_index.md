---
title: InterruptionTokenSource
type: docs
weight: 0
url: /php-java/interruptiontokensource/
---

# InterruptionTokenSource class

 Represents the source of  InterruptionToken.
 

## Constructors

| name | description |
| --- | --- |
| [InterruptionTokenSource](/slides/php-java/interruptiontokensource/interruptiontokensource/)() | Creates a new InterruptionTokenSource. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getToken](/slides/php-java/interruptiontokensource/gettoken/)() | InterruptionToken | Returns new token binded to this InterruptionTokenSource. |
| [interrupt](/slides/php-java/interruptiontokensource/interrupt/)() | void | Initialize request for interruption. |
| [isInterruptionRequested](/slides/php-java/interruptiontokensource/isinterruptionrequested/)() | boolean | Returns true if interruption requested, false otherwise. |
