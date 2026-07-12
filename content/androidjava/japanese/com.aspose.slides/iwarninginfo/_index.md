---
title: IWarningInfo
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a base interface for all warnings.
type: docs
url: /ja/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

すべての警告の基本インターフェイスを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | 受信者が null でない場合、指定された受信者に警告を終了し、受信者が操作を中止することを決定した場合は AbortRequestedException をスローします。 |
| [getWarningType()](#getWarningType--) | 警告のタイプを返します。 |
| [getDescription()](#getDescription--) | この警告の人間が読める説明を返します。 |

### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

受信者が null でない場合、指定された受信者に警告を終了し、受信者が操作を中止することを決定した場合は AbortRequestedException をスローします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | 受信オブジェクト [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

警告のタイプを返します。読み取り専用 [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType)。

**戻り値:**
int

### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

この警告の人間が読める説明を返します。読み取り専用 String。

**戻り値:**
java.lang.String