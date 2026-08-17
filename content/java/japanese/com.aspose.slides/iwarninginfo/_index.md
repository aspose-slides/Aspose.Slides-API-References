---
title: IWarningInfo
second_title: Aspose.Slides for Java API Reference
description: すべての警告の基本インターフェイスを表します。
type: docs
url: /ja/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

すべての警告の基本インターフェイスを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | receiver が null でない場合、指定された受信者に警告を終了し、受信者が操作の中止を決定した場合は AbortRequestedException をスローします。 |
| [getWarningType()](#getWarningType--) | 警告の種類を返します。 |
| [getDescription()](#getDescription--) | この警告の人が読める説明を返します。 |

### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

receiver が null でない場合、指定された受信者に警告を終了し、受信者が操作の中止を決定した場合は AbortRequestedException をスローします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | 受信者オブジェクト [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

警告の種類を返します。 読み取り専用 [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**戻り値:**
int

### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

この警告の人が読める説明を返します。 読み取り専用 String.

**戻り値:**
java.lang.String