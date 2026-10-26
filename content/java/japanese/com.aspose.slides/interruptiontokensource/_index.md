---
title: InterruptionTokenSource
second_title: Aspose.Slides の Java API リファレンス
description: ソースを表します。
type: docs
url: /ja/com.aspose.slides/interruptiontokensource/
---
**継承:**
java.lang.Object
```
public class InterruptionTokenSource
```

[InterruptionToken](../../com.aspose.slides/interruptiontoken) のソースを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [InterruptionTokenSource()](#InterruptionTokenSource--) | 新しい[InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)を作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getToken()](#getToken--) | この[InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)にバインドされた新しいトークンを返します。 |
| [isInterruptionRequested()](#isInterruptionRequested--) | 中断が要求された場合は true、そうでなければ false を返します。 |
| [interrupt()](#interrupt--) | 中断要求を初期化します。 |

### InterruptionTokenSource() {#InterruptionTokenSource--}
```
public InterruptionTokenSource()
```

新しい[InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)を作成します。

### getToken() {#getToken--}
```
public final InterruptionToken getToken()
```

この[InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)にバインドされた新しいトークンを返します。

**戻り値:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)

### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

中断が要求された場合は true、そうでなければ false を返します。

**戻り値:**
boolean

### interrupt() {#interrupt--}
```
public final void interrupt()
```

中断要求を初期化します。