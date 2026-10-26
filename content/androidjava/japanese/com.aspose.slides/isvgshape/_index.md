---
title: ISvgShape
second_title: Android 用 Aspose.Slides Java API リファレンス
description: SVG シェイプのオプションを表します。
type: docs
url: /ja/com.aspose.slides/isvgshape/
---```
public interface ISvgShape
```

SVG シェイプのオプションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [setEventHandler(int eventType, String handler)](#setEventHandler-int-java.lang.String-) | シェイプのイベントハンドラを設定します |
| [getId()](#getId--) | シェイプの ID を設定または取得します |
| [setId(String value)](#setId-java.lang.String-) | シェイプの ID を設定または取得します |

### setEventHandler(int eventType, String handler) {#setEventHandler-int-java.lang.String-}
```
public abstract void setEventHandler(int eventType, String handler)
```

シェイプのイベントハンドラを設定します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| eventType | int | イベントの種類。 |
| handler | java.lang.String | イベントを処理する Javascript 関数。null 値はハンドラを削除します。 |

### getId() {#getId--}
```
public abstract String getId()
```

シェイプの ID を設定または取得します

**戻り値:**
java.lang.String

### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

シェイプの ID を設定または取得します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |