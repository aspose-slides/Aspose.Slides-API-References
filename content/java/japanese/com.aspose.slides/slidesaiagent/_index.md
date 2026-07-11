---
title: SlidesAIAgent
second_title: Aspose.Slides for Java API リファレンス
description: プレゼンテーションの処理のための AI 機能を提供します。
type: docs
url: /ja/com.aspose.slides/slidesaiagent/
---
**継承:**
java.lang.Object
```
public class SlidesAIAgent
```

プレゼンテーションの処理のための AI 機能を提供します。

## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | カスタム AI クライアントを使用して [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) の新しいインスタンスを初期化します。 |
| [SlidesAIAgent()](#SlidesAIAgent--) | 組み込みの [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) を使用し、デフォルト構成で [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) の新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | AI を使用してプレゼンテーションを指定された言語に翻訳します（同期バージョン）。 |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | テキストの説明からプレゼンテーションのインスタンスを生成します。 |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | テキストの説明からプレゼンテーションのインスタンスを生成します。 |

### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

カスタム AI クライアントを使用して [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) の新しいインスタンスを初期化します。このオーバーロードを使用して AI プロバイダーを指定したり、独自の LLM を提供したり、接続をカスタマイズしたりできます（例として、独自の java.net.HttpURLConnection を提供する場合）。[IAIWebClient](../../com.aspose.slides/iaiwebclient) の任意の実装を使用できます。デフォルト構成で組み込みの [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) を使用するには、 SlidesAIAgent() オーバーロードを使用してください。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI クライアントインスタンス。[IAIWebClient](../../com.aspose.slides/iaiwebclient) の任意の実装を使用できます。 |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

組み込みの [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) を使用し、デフォルト構成で [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) の新しいインスタンスを初期化します。クライアントは Aspose の独自 LLM に接続し、追加の構成は不要です。別の AI クライアントを使用するには、 SlidesAIAgent(IAIWebClient) オーバーロードを使用してください。

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

AI を使用してプレゼンテーションを指定された言語に翻訳します（同期バージョン）。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 対象のプレゼンテーション |
| language | java.lang.String | 対象言語 |

--------------------

以下の例は、パラメーターなしの SlidesAIAgent() コンストラクターで作成され、Aspose の独自 LLM に接続するデフォルトの [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) を使用しています。別の AI プロバイダーを使用したり、独自の LLM を提供したり、接続をカスタマイズしたりするには（例として、独自の java.net.HttpURLConnection を提供する場合）、[IAIWebClient](../../com.aspose.slides/iaiwebclient) の実装を SlidesAIAgent(IAIWebClient) コンストラクターに渡してください。

```
Presentation presentation = new Presentation("Presentation.pptx");
 try {
     IAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", "apiKey", null);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
     aiAgent.translate(presentation, "spanish");
     presentation.save("translated.pptx", SaveFormat.Pptx);
 } finally {
     if (presentation != null) presentation.dispose();
 }
``` |

### generatePresentation(String description, int presentationContentAmount) {#generatePresentation-java.lang.String-int-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount)
```

テキストの説明からプレゼンテーションのインスタンスを生成します。必要な言語でトピック、アイデア、引用、またはテキストスニペットを提供してください。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| description | java.lang.String | トピック、アイデア、引用、またはテキストスニペット。 |
| presentationContentAmount | int | 生成されるプレゼンテーションのコンテンツ量。 |

```
String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
 OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null);
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
     IPresentation pres = aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief);
     pres.save("result.pptx", SaveFormat.Pptx);
 } finally {
     if (aiWebClient != null) aiWebClient.close();
 }
``` |

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation)

### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

テキストの説明からプレゼンテーションのインスタンスを生成します。必要な言語でトピック、アイデア、引用、またはテキストスニペットを提供してください。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| description | java.lang.String | トピック、アイデア、引用、またはテキストスニペット。 |
| presentationContentAmount | int | 生成されるプレゼンテーションのコンテンツ量。 |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | レイアウトとデザインのテンプレートとして使用するプレゼンテーションで、デフォルトテンプレートを置き換えます。 |

--------------------

以下の例は、パラメーターなしの SlidesAIAgent() コンストラクターで作成され、Aspose の独自 LLM に接続するデフォルトの [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) を使用しています。別の AI プロバイダーを使用したり、独自の LLM を提供したり、接続をカスタマイズしたりするには（例として、独自の java.net.HttpURLConnection を提供する場合）、[IAIWebClient](../../com.aspose.slides/iaiwebclient) の実装を SlidesAIAgent(IAIWebClient) コンストラクターに渡してください。

```
String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
 IPresentation template = new Presentation("masterPresentation.pptx");
 try {
     OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null);
     try {
         SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
         IPresentation pres =
             aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief, template);
         pres.save("result.pptx", SaveFormat.Pptx);
     } finally {
         if (aiWebClient != null) aiWebClient.close();
     }
 } finally {
     if (template != null) template.dispose();
 }
``` |

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation)