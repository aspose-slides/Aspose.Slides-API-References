---
title: LinkEmbedDecision
type: docs
weight: 0
url: /php-java/linkembeddecision/
---

# LinkEmbedDecision class

 Determines how object will be processed during saving.
 

## Constants

| name | description |
| --- | --- |
| Embed | Object should be embedded to a generated file if possible. If embedding is imposible, GetUrl will be called and, depending on result, object will be referrenced by URL or ignored. |
| Ignore | Object will be ignored. |
| Link | Object will be stored externally, referrenced by URL |

