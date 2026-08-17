---
title: IInterruptionToken
second_title: Aspose.Slides for Java API リファレンス
description: このクラスは、長時間実行されるタスクに対して割り込みが要求されたかどうかを通知するために使用するトークンを表します。
type: docs
url: /ja/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

このクラスは、長時間実行されるタスクに対して割り込みが要求されたかどうかを通知するために使用するトークンを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | 割り込みが要求された場合に true を返します。 |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | 割り込みが要求された場合に例外をスローします。 |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

割り込みが要求された場合に true を返します。

**戻り値:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```

割り込みが要求された場合に例外をスローします。