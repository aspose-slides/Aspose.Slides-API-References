---
title: CustomData
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: カスタム データのコンテナを表します。
type: docs
url: /ja/com.aspose.slides/customdata/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.ICustomData](../../com.aspose.slides/icustomdata), com.aspose.slides.IDOMObject  
```
public class CustomData implements ICustomData, IDOMObject
```

カスタム データのコンテナを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTags()](#getTags--) | Customer Data Tags コレクションを返します。 |
| [getCustomXmlParts()](#getCustomXmlParts--) | カスタム XML パーツ コレクションを返します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getTags() {#getTags--}
```
public final ITagCollection getTags()
```

Customer Data Tags コレクションを返します。 読み取り専用 [ITagCollection](../../com.aspose.slides/itagcollection)。

**返り値:**  
[ITagCollection](../../com.aspose.slides/itagcollection)
### getCustomXmlParts() {#getCustomXmlParts--}
```
public final ICustomXmlPartCollection getCustomXmlParts()
```

カスタム XML パーツ コレクションを返します。 読み取り専用 [ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection)。

**返り値:**  
[ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。 読み取り専用 IDOMObject。

**返り値:**  
com.aspose.slides.IDOMObject