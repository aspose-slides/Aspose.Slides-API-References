---
title: ITab
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: テキストのタブ設定を表します。
type: docs
url: /ja/com.aspose.slides/itab/
---
**すべての実装インターフェイス:**  
java.lang.Comparable  
```
public interface ITab extends Comparable
```

テキストのタブ設定を表します。  

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPosition()](#getPosition--) | タブの位置を取得または設定します。 |
| [setPosition(double value)](#setPosition-double-) | タブの位置を取得または設定します。 |
| [getAlignment()](#getAlignment--) | タブの配置スタイルを取得または設定します。 |
| [setAlignment(int value)](#setAlignment-int-) | タブの配置スタイルを取得または設定します。 |

### getPosition() {#getPosition--}
```
public abstract double getPosition()
```

タブの位置を取得または設定します。 このプロパティを設定すると、コレクション内のタブのインデックスが変わり、Enumerator が無効になる可能性があります。 読み取り/書き込み double.

**戻り値:**
double

### setPosition(double value) {#setPosition-double-}
```
public abstract void setPosition(double value)
```

タブの位置を取得または設定します。 このプロパティを設定すると、コレクション内のタブのインデックスが変わり、Enumerator が無効になる可能性があります。 読み取り/書き込み double.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

タブの配置スタイルを取得または設定します。 読み取り/書き込み [TabAlignment](../../com.aspose.slides/tabalignment).

**戻り値:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

タブの配置スタイルを取得または設定します。 読み取り/書き込み [TabAlignment](../../com.aspose.slides/tabalignment).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  