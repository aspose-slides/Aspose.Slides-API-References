---
title: IVbaReferenceFactory
second_title: Aspose.Slides for Android via Java API Reference
description: COM インターフェイスを使用して VBA プロジェクト参照を作成できます
type: docs
url: /ja/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

COM インターフェイスを使用して VBA プロジェクト参照を作成できます
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | 新しい OLE Automation タイプ ライブラリ参照を作成します。 |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```

新しい OLE Automation タイプ ライブラリ参照を作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | VBA プロジェクト参照の名前 String |
| libid | java.lang.String | Automation タイプ ライブラリの識別子 String |

**戻り値:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - 新しい OLE Automation タイプ ライブラリ参照 [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)