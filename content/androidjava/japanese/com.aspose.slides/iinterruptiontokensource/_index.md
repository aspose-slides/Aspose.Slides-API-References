---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Android via Java API Reference
description: ソースを表します。
type: docs
url: /ja/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) のソースを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getToken()](#getToken--) | この [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) にバインドされた新しいトークンを返します。 |
| [isInterruptionRequested()](#isInterruptionRequested--) | 割り込みが要求されていれば true、そうでなければ false を返します。 |
| [interrupt()](#interrupt--) | 割り込みの要求を初期化します。 |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```

この [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) にバインドされた新しいトークンを返します。

**戻り値:**  
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

割り込みが要求されていれば true、そうでなければ false を返します。

**戻り値:**  
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```

割り込みの要求を初期化します。