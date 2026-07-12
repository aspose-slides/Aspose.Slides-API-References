---
title: SensitivityLabel
second_title: Java API リファレンスによる Android 向け Aspose.Slides
description: Microsoft Purview Information Protection の感度ラベルを表します。
type: docs
url: /ja/com.aspose.slides/sensitivitylabel/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
```
public final class SensitivityLabel implements ISensitivityLabel
```

Microsoft Purview Information Protection の感度ラベルを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getId()](#getId--) | 感度ラベルの ID を取得または設定します。 |
| [setId(String value)](#setId-java.lang.String-) | 感度ラベルの ID を取得または設定します。 |
| [getSiteId()](#getSiteId--) | 感度ラベルを記述する感度ラベル ポリシーに対応する Azure Active Directory (Azure AD) サイト識別子を取得または設定します。 |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | 感度ラベルを記述する感度ラベル ポリシーに対応する Azure Active Directory (Azure AD) サイト識別子を取得または設定します。 |
| [isEnabled()](#isEnabled--) | 感度ラベルが有効かどうかを示します。 |
| [setEnabled(boolean value)](#setEnabled-boolean-) | 感度ラベルが有効かどうかを示します。 |
| [isRemoved()](#isRemoved--) | 感度ラベルが削除されたかどうかを示します。 |
| [setRemoved(boolean value)](#setRemoved-boolean-) | 感度ラベルが削除されたかどうかを示します。 |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | 感度ラベルの割り当て方法を取得または設定します。 |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | 感度ラベルの割り当て方法を取得または設定します。 |
| [getContentMarkTypes()](#getContentMarkTypes--) | ファイルに適用すべきコンテンツマーキングの種類のリストを取得します。 |

### getId() {#getId--}
```
public final String getId()
```

感度ラベルの ID を取得または設定します。 読み取り/書き込み String.

**戻り値:**
java.lang.String

### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```

感度ラベルの ID を取得または設定します。 読み取り/書き込み String.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```

感度ラベルを記述する感度ラベル ポリシーに対応する Azure Active Directory (Azure AD) サイト識別子を取得または設定します。 読み取り/書き込み java.util.UUID.

**戻り値:**
java.util.UUID

### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```

感度ラベルを記述する感度ラベル ポリシーに対応する Azure Active Directory (Azure AD) サイト識別子を取得または設定します。 読み取り/書き込み java.util.UUID.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```

感度ラベルが有効かどうかを示します。

**戻り値:**
boolean

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```

感度ラベルが有効かどうかを示します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```

感度ラベルが削除されたかどうかを示します。

**戻り値:**
boolean

### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```

感度ラベルが削除されたかどうかを示します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```

感度ラベルの割り当て方法を取得または設定します。 読み取り/書き込み [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**戻り値:**
int

### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```

感度ラベルの割り当て方法を取得または設定します。 読み取り/書き込み [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

ファイルに適用すべきコンテンツマーキングの種類のリストを取得します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - コンテンツタイプのリスト [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)