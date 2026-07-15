---
title: EmbeddingLevel
second_title: Aspose.Slides for Android 之 Java API 參考
description: 表示嵌入字型的授權權利。
type: docs
url: /zh-hant/com.aspose.slides/embeddinglevel/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

表示嵌入字型的授權權利。
## 欄位

| 欄位 | 說明 |
| --- | --- |
| [Installable](#Installable) | 設定為此的字型表示它們可以被嵌入並永久安裝在遠端系統上，供應用程式使用。 |
| [Restricted](#Restricted) | 只設定此位元的字型在未先取得合法所有者的許可前，禁止以任何方式修改、嵌入或交換。 |
| [PreviewPrint](#PreviewPrint) | 設定此位元時，字型可以被嵌入，且可暫時載入遠端系統。 |
| [Editable](#Editable) | 設定此位元時，字型可以被嵌入，但只能暫時安裝於其他系統上。 |
| [NoSubsetting](#NoSubsetting) | 設定此位元時，嵌入前不得對字型進行子集化。 |
| [BitmapOnly](#BitmapOnly) | 設定此位元時，僅允許嵌入字型中包含的點陣圖。 |
### 可安裝 {#Installable}
```
public static final int Installable
```


設定此位元的字型表示它們可以被嵌入並永久安裝在遠端系統上，供應用程式使用。遠端系統的使用者取得與原始購買者相同的權利、義務與授權，並受相同的最終使用者授權協議、版權、設計專利及/或商標約束。

### 受限 {#Restricted}
```
public static final int Restricted
```


只設定此位元的字型在未先取得合法所有者的許可前，禁止以任何方式修改、嵌入或交換。

### 預覽列印 {#PreviewPrint}
```
public static final int PreviewPrint
```


設定此位元時，字型可以被嵌入，且可暫時載入遠端系統。包含「預覽與列印」字型的文件必須以「唯讀」方式開啟；不可對文件進行編輯。

### 可編輯 {#Editable}
```
public static final int Editable
```


設定此位元時，字型可以被嵌入，但只能暫時安裝於其他系統。與「預覽與列印」字型不同，包含「可編輯」字型的文件可開啟閱讀，允許編輯，且變更可被儲存。

### 不分割子集 {#NoSubsetting}
```
public static final int NoSubsetting
```


設定此位元時，嵌入前不得對字型進行子集化。位元 0-3 與 9 中指定的其他嵌入限制亦同時適用。

### 僅點陣圖 {#BitmapOnly}
```
public static final int BitmapOnly
```


設定此位元時，僅允許嵌入字型中包含的點陣圖。輪廓資料不可嵌入。若字型中沒有可用的點陣圖，則此字型視為無法嵌入，嵌入服務將失敗。