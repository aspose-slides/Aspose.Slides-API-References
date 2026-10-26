---
title: IInterruptionToken
second_title: Aspose.Slides for Android via Java API Reference
description: このクラスは、長時間実行タスクに対して中断が要求されたかどうかを示すために使用するトークンを表します。
type: docs
url: /ja/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

このクラスは、長時間実行タスクに対して中断が要求されたかどうかを示すために使用するトークンを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | 中断が要求された場合に true を返します。 |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | 中断が要求された場合に例外をスローします。 |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


中断が要求された場合に true を返します。

**戻り値:**  
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```


中断が要求された場合に例外をスローします。