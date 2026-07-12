---
title: SlidesAIAgent
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: プレゼンテーションの処理向けに AI 機能を提供します。
type: docs
url: /ja/com.aspose.slides/slidesaiagent/
---
**継承:**
java.lang.Object
```
public class SlidesAIAgent
```

プレゼンテーションの処理向けに AI 機能を提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | SlidesAIAgent コンストラクタ |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | AI を使用して、指定された言語にプレゼンテーションを翻訳します（同期バージョン）。 |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | テキスト記述からプレゼンテーション インスタンスを生成します。 |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | テキスト記述からプレゼンテーション インスタンスを生成します。 |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```


SlidesAIAgent コンストラクタ

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI クライアント インスタンス |

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public void translate(IPresentation presentation, String language)
```


AI を使用して、指定された言語にプレゼンテーションを翻訳します（同期バージョン）。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 対象のプレゼンテーション |
| language | java.lang.String | 対象言語

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


テキスト記述からプレゼンテーション インスタンスを生成します。必要な言語でトピック、アイデア、引用、またはテキストスニペットを提供してください。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| description | java.lang.String | トピック、アイデア、引用、またはテキストスニペット。 |
| presentationContentAmount | int | 生成されたプレゼンテーションのコンテンツ量。

```
String prompt = "Generate a presentation about Aspose.Slides for Android via Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
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


テキスト記述からプレゼンテーション インスタンスを生成します。必要な言語でトピック、アイデア、引用、またはテキストスニペットを提供してください。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| description | java.lang.String | トピック、アイデア、引用、またはテキストスニペット。 |
| presentationContentAmount | int | 生成されたプレゼンテーションのコンテンツ量。 |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | レイアウトとデザイン用のテンプレートとして使用するプレゼンテーション（既定のテンプレートを置き換えます）。

```
String prompt = "Generate a presentation about Aspose.Slides for Android via Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
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