---
title: OpenAIWebClient
second_title: Aspose.Sildes for .NET API Reference
description: Creates instance of OpenAI Web client.
type: docs
weight: 10
url: /aspose.slides.ai/openaiwebclient/openaiwebclient/
---

## OpenAIWebClient(string, string, string) {#constructor}

Creates instance of OpenAI Web client.

```csharp
public OpenAIWebClient(string model, string apiKey, string organizationId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| model | String | OpenAI language model. Possible values: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | String | OpenAI API key |
| organizationId | String | Organization ID (optional) |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | API key value can't be null or empty |
| ArgumentException | Text model value can't be null or empty |

### See Also

* class [OpenAIWebClient](../../openaiwebclient)
* namespace [Aspose.Slides.AI](../../openaiwebclient)
* assembly [Aspose.Slides](../../../)

---

## OpenAIWebClient(string, string, string, HttpClient) {#constructor_1}

Creates instance of OpenAI Web client.

```csharp
public OpenAIWebClient(string model, string apiKey, string organizationId, HttpClient httpClient)
```

| Parameter | Type | Description |
| --- | --- | --- |
| model | String | OpenAI language model. Possible values: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | String | OpenAI API key |
| organizationId | String | Organization ID (optional) |
| httpClient | HttpClient | An externally managed `HttpClient` instance. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | API key value can't be null or empty |
| ArgumentException | Text model value can't be null or empty |

### See Also

* class [OpenAIWebClient](../../openaiwebclient)
* namespace [Aspose.Slides.AI](../../openaiwebclient)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
