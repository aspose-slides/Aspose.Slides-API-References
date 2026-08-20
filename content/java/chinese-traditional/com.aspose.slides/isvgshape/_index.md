---
title: ISvgShape
second_title: Aspose.Slides for Java API 參考
description: 表示 SVG 形狀的選項。
type: docs
url: /zh-hant/com.aspose.slides/isvgshape/
---```
public interface ISvgShape
```

表示 SVG 形狀的選項。
## 方法

| 方法 | 說明 |
| --- | --- |
| [setEventHandler(int eventType, String handler)](#setEventHandler-int-java.lang.String-) | 設定形狀的事件處理程式 |
| [getId()](#getId--) | 設定或取得形狀的 id |
| [setId(String value)](#setId-java.lang.String-) | 設定或取得形狀的 id |
### setEventHandler(int eventType, String handler) {#setEventHandler-int-java.lang.String-}
```
public abstract void setEventHandler(int eventType, String handler)
```

設定形狀的事件處理程式

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| eventType | int | 事件的類型。 |
| handler | java.lang.String | Javascript 函式，用於處理事件。Null 值會移除處理函式。 |

### getId() {#getId--}
```
public abstract String getId()
```

設定或取得形狀的 id

**傳回值:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

設定或取得形狀的 id

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |