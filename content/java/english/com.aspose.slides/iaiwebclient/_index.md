---
title: IAIWebClient
second_title: Aspose.Slides for Java API Reference
description: AI Web client interface.
type: docs
url: /com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

AI Web client interface. This interface enables to substitute different AI language models. Classes that implement this interface are supposed to be used along with
## Methods

| Method | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Sends a chat instruction to the AI model and returns response message. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```


Sends a chat instruction to the AI model and returns response message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String | The instruction or message to be processed by the AI model |

**Returns:**
java.lang.String
