---
title: InterruptionToken
second_title: Aspose.Slides の Java API リファレンス
description: このクラスは、長時間実行されるタスクに対して割り込みが要求されたかどうかを通知するために使用するトークンを表します。
type: docs
url: /ja/com.aspose.slides/interruptiontoken/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

このクラスは、長時間実行されるタスクに対して割り込みが要求されたかどうかを通知するために使用するトークンを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getNone()](#getNone--) | 空の割り込みトークンを表します。 |
| [isInterruptionRequested()](#isInterruptionRequested--) | 割り込みが要求された場合に true を返します。 |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | 割り込みが要求された場合に例外をスローします。 |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```

空の割り込みトークンを表します。

--------------------

このトークンを使用する場合、[InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) によって長時間実行される操作は決して割り込まれません。

**戻り値:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

割り込みが要求された場合に true を返します。

**戻り値:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```

割り込みが要求された場合に例外をスローします。