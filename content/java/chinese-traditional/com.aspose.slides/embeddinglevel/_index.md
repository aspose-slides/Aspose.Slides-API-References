---
title: EmbeddingLevel
second_title: Aspose.Slides for Java API 參考文件
description: 表示嵌入字型的授權權利。
type: docs
url: /zh-hant/com.aspose.slides/embeddinglevel/
---
**繼承：**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

表示嵌入字型的授權權利。

## 欄位

| 欄位 | 說明 |
| --- | --- |
| [Installable](#Installable) | 具有此設定的字型表示它們可以被嵌入，並由應用程式永久安裝於遠端系統。 |
| [Restricted](#Restricted) | 僅設定此位元的字型在未先取得合法所有者的許可前，禁止以任何方式修改、嵌入或交換。 |
| [PreviewPrint](#PreviewPrint) | 當此位元被設定時，該字型可以被嵌入，並暫時載入遠端系統。 |
| [Editable](#Editable) | 當此位元被設定時，該字型可以被嵌入，但僅能暫時安裝於其他系統。 |
| [NoSubsetting](#NoSubsetting) | 當此位元被設定時，該字型在嵌入之前不得進行子集化。 |
| [BitmapOnly](#BitmapOnly) | 當此位元被設定時，僅允許嵌入字型內含的點陣圖。 |

### 可安裝的 {#Installable}
```
public static final int Installable
```

具有此設定的字型表示它們可以被嵌入，並由應用程式永久安裝於遠端系統。遠端系統的使用者取得與字型原始購買者相同的權利、義務與授權，並受到與原始購買者相同的最終使用者授權協議、版權、外觀專利及/或商標的限制。

### 受限的 {#Restricted}
```
public static final int Restricted
```

僅設定此位元的字型在未先取得合法所有者的許可前，禁止以任何方式修改、嵌入或交換。

### 預覽列印 {#PreviewPrint}
```
public static final int PreviewPrint
```

當此位元被設定時，該字型可以被嵌入，並暫時載入遠端系統。包含預覽與列印字型的文件必須以「唯讀」模式開啟；文件不能被編輯。

### 可編輯的 {#Editable}
```
public static final int Editable
```

當此位元被設定時，該字型可以被嵌入，但僅能暫時安裝於其他系統。與預覽與列印字型相反，包含可編輯字型的文件可開啟閱讀，允許編輯，且變更可以被儲存。

### 不允許子集化 {#NoSubsetting}
```
public static final int NoSubsetting
```

當此位元被設定時，該字型在嵌入之前不得進行子集化。位元 0-3 與 9 所指定的其他嵌入限制亦同樣適用。

### 僅點陣圖 {#BitmapOnly}
```
public static final int BitmapOnly
```

當此位元被設定時，僅允許嵌入字型中所包含的點陣圖。輪廓資料不得嵌入。若字型中沒有可用的點陣圖，則該字型視為不可嵌入，嵌入服務將失敗。