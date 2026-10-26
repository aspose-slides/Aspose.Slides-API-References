---
title: ITemplateEngine
second_title: Aspose.Slides for Android via Java API Reference
description: テンプレートとデータのペアを変換し、通常はHTMLになる出力を生成するテンプレートエンジンを表します。
type: docs
url: /ja/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

テンプレートとデータのペアを変換し、通常はHTMLになる出力を生成するテンプレートエンジンを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | テンプレートをテンプレートコレクションに追加します。 |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | 指定されたキーとモデルオブジェクトでテンプレートを変換し、出力を生成します。 |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```


テンプレートをテンプレートコレクションに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| key | java.lang.String | テンプレートコレクション内のテンプレートのキー。 |
| template | java.lang.String | テンプレートの内容。 |
| modelType | com.aspose.ms.System.Type | テンプレート用モデルオブジェクトの型。 |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```


指定されたキーとモデルオブジェクトでテンプレートを変換し、出力を生成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| key | java.lang.String | テンプレートコレクション内のテンプレートのキー。 |
| model | java.lang.Object | 変換用データを含むモデルオブジェクト。 |

**戻り値:**
java.lang.String - 結果の出力文字列。