---
title: VbaReferenceFactory
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: COM インターフェイスを介して VBA プロジェクト参照を作成できます
type: docs
url: /ja/com.aspose.slides/vbareferencefactory/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

COM インターフェイスを介して VBA プロジェクト参照を作成できます
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getInstance()](#getInstance--) | VBA プロジェクト参照ファクトリの静的インスタンスです。 |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | 新しい OLE Automation タイプ ライブラリ参照を作成します。 |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```

### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```

VBA プロジェクト参照ファクトリの静的インスタンスです。読み取り専用 [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)。

**戻り値:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```

新しい OLE Automation タイプ ライブラリ参照を作成します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**戻り値:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - 新しい OLE Automation タイプ ライブラリ参照