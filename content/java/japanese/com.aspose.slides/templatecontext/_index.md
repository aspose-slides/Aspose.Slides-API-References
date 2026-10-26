---
title: TemplateContext
second_title: Aspose.Slides の Java API リファレンス
description: テンプレートエンジン用のモデルオブジェクトインターフェイスを表します。
type: docs
url: /ja/com.aspose.slides/templatecontext/
---
**継承:**  
java.lang.Object
```
public final class TemplateContext<TObject>
```

テンプレートエンジン用のモデルオブジェクトインターフェイスを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | 子テンプレートコンテキストを作成します。 |
| [getObject()](#getObject--) | モデルオブジェクトを返します。 |
| [getOutput()](#getOutput--) | ホストドキュメントの出力要素のコレクションを返します。 |
| [getLocal()](#getLocal--) | 現在のテンプレートコンテキストのローカルストレージを返します。 |
| [getGlobal()](#getGlobal--) | ホストドキュメントのグローバルストレージを返します。 |

### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```

子テンプレートコンテキストを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| subModel | TSubModel | 子モデルオブジェクト。 |

**戻り値:**
[TemplateContext](../../com.aspose.slides/templatecontext) - 指定されたモデルと親の出力コレクション、グローバルストレージを持つ新しいテンプレートコンテキスト。

### getObject() {#getObject--}
```
public final TObject getObject()
```

モデルオブジェクトを返します。読み取り専用 Object。

**戻り値:**
TObject

### getOutput() {#getOutput--}
```
public final Output getOutput()
```

ホストドキュメントの出力要素のコレクションを返します。読み取り専用 [Output](../../com.aspose.slides/output)(\#getOutput.getOutput)。

**戻り値:**
[Output](../../com.aspose.slides/output)

### getLocal() {#getLocal--}
```
public final Storage getLocal()
```

現在のテンプレートコンテキストのローカルストレージを返します。読み取り専用 [Storage](../../com.aspose.slides/storage)。

**戻り値:**
[Storage](../../com.aspose.slides/storage)

### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

ホストドキュメントのグローバルストレージを返します。読み取り専用 [Storage](../../com.aspose.slides/storage)。

**戻り値:**
[Storage](../../com.aspose.slides/storage)