---
title: IWarningCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 警告を受け取るクラス向けインターフェイス
type: docs
url: /ja/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

警告を受け取るクラス向けインターフェイス
## メソッド

| メソッド | 説明 |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | 警告を受け取り、操作を中止すべきかどうかを決定するコールバックメソッド。 |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```


警告を受け取り、操作を中止すべきかどうかを決定するコールバックメソッド。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | 処理する警告。 |

**戻り値:**
int - 中止の決定 [ReturnAction](../../com.aspose.slides/returnaction).