---
title: OpenAIWebClient
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/openaiwebclient/
---
## OpenAIWebClient 类

 内置轻量级 OpenAI Web 客户端

### OpenAIWebClient {#OpenAIWebClient}

| 名称 | 描述 |
| --- | --- |
| OpenAIWebClient(String, String, String) | 创建 OpenAI Web 客户端的实例。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| model | String | OpenAI 语言模型。可能的取值：- gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | String | OpenAI API 密钥 |
| organizationId | String | 组织 ID（可选） |

**返回值：**
OpenAIWebClient

**错误**

| 错误 | 条件 |
| --- | --- |
 | ArgumentException | 文本模型值不能为空或为空 |


---

### OpenAIWebClient {#OpenAIWebClient}

| 名称 | 描述 |
| --- | --- |
| OpenAIWebClient(String, String, String, HttpURLConnection) | 创建 OpenAI Web 客户端的实例。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| model | String | OpenAI 语言模型。可能的取值：- gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | String | OpenAI API 密钥 |
| organizationId | String | 组织 ID（可选） |
| httpClient | HttpURLConnection | 外部管理的 `HttpURLConnection` 实例。 |

**返回值：**
OpenAIWebClient

**错误**

| 错误 | 条件 |
| --- | --- |
 | ArgumentException | 文本模型值不能为空或为空 |


---

### callChat {#callChat}

| 名称 | 描述 |
| --- | --- |
| callChat (String) | 使用外部管理的实例向 AI 模型发送聊天指令，并返回给定指令的响应消息。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| instruction | String | 要由 AI 模型处理的指令或消息 |

**返回值：**
String

**异常**

| 错误 | 条件 |
| --- | --- |
 | com.aspose.ms.System.OperationCanceledException | 如果当前线程在等待时被中断。 |


---

### close {#close}

| 名称 | 描述 |
| --- | --- |
| close () | 释放此实例使用的资源。 |

**返回值：**
void


---

### createConversation {#createConversation}

| 名称 | 描述 |
| --- | --- |
| createConversation () | 创建会话实例。与常规 AI 调用不同，会话会保留完整的上下文。 |

**返回值：**
OpenAIConversation