---
title: TemplateContext
second_title: Aspose.Slides for Android via Java API リファレンス
description: テンプレート エンジン用のモデルオブジェクト インターフェイスを表します。
type: docs
url: /ja/com.aspose.slides/templatecontext/
---
**継承:**
java.lang.Object
```
public final class TemplateContext<TObject>
```


テンプレートエンジン用のモデルオブジェクト インターフェイスを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | 子テンプレート コンテキストを作成します。 |
| [getObject()](#getObject--) | モデル オブジェクトを返します。 |
| [getOutput()](#getOutput--) | ホスト ドキュメントの出力要素のコレクションを返します。 |
| [getLocal()](#getLocal--) | 現在のテンプレート コンテキストのローカル ストレージを返します。 |
| [getGlobal()](#getGlobal--) | ホスト ドキュメントのグローバル ストレージを返します。 |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```


子テンプレート コンテキストを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| subModel | TSubModel | 子モデル オブジェクト。 |

**戻り値:**
[TemplateContext](../../com.aspose.slides/templatecontext) - 指定されたモデルと親の出力コレクションおよびグローバル ストレージを持つ新しいテンプレート コンテキスト。
### getObject() {#getObject--}
```
public final TObject getObject()
```


モデル オブジェクトを返します。 読み取り専用 Object。

**戻り値:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


ホスト ドキュメントの出力要素のコレクションを返します。 読み取り専用 [Output](../../com.aspose.slides/output)(\#getOutput.getOutput)。

**戻り値:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```


現在のテンプレート コンテキストのローカル ストレージを返します。 読み取り専用 [Storage](../../com.aspose.slides/storage)。

**戻り値:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


ホスト ドキュメントのグローバル ストレージを返します。 読み取り専用 [Storage](../../com.aspose.slides/storage)。

**戻り値:**
[Storage](../../com.aspose.slides/storage)