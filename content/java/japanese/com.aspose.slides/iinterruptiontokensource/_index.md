---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Java API Reference
description: ソースを表します。
type: docs
url: /ja/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)のソースを表します。

## メソッド

| Method | Description |
| --- | --- |
| [getToken()](#getToken--) | この[IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource)にバインドされた新しいトークンを返します。 |
| [isInterruptionRequested()](#isInterruptionRequested--) | 中断が要求された場合は true を返し、そうでない場合は false を返します。 |
| [interrupt()](#interrupt--) | 中断のリクエストを初期化します。 |

### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```

この[IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource)にバインドされた新しいトークンを返します。

**戻り値:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

中断が要求された場合は true を返し、そうでない場合は false を返します。

**戻り値:**
boolean

### interrupt() {#interrupt--}
```
public abstract void interrupt()
```

中断のリクエストを初期化します。