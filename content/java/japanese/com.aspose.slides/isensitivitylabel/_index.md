---
title: ISensitivityLabel
second_title: Aspose.Slides for Java API Reference
description: Represents the sensitivity label from Microsoft Purview Information Protection.
type: docs
url: /ja/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

Microsoft Purview Information Protection からの感度ラベルを表します。

## メソッド

| Method | Description |
| --- | --- |
| [getId()](#getId--) | 感度ラベルの ID を取得または設定します。 |
| [setId(String value)](#setId-java.lang.String-) | 感度ラベルの ID を取得または設定します。 |
| [getSiteId()](#getSiteId--) | 感度ラベルを説明する感度ラベル ポリシーに対応する Azure Active Directory (Azure AD) サイト識別子を取得または設定します。 |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | 感度ラベルを説明する感度ラベル ポリシーに対応する Azure Active Directory (Azure AD) サイト識別子を取得または設定します。 |
| [isEnabled()](#isEnabled--) | 感度ラベルが有効かどうかを示します。 |
| [setEnabled(boolean value)](#setEnabled-boolean-) | 感度ラベルが有効かどうかを示します。 |
| [isRemoved()](#isRemoved--) | 感度ラベルが削除されたかどうかを示します。 |
| [setRemoved(boolean value)](#setRemoved-boolean-) | 感度ラベルが削除されたかどうかを示します。 |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | 感度ラベルの割り当て方法を取得または設定します。 |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | 感度ラベルの割り当て方法を取得または設定します。 |
| [getContentMarkTypes()](#getContentMarkTypes--) | ファイルに適用すべきコンテンツ マーキングのタイプの一覧を取得します。 |

### getId() {#getId--}
```
public abstract String getId()
```

感度ラベルの ID を取得または設定します。 読み取り/書き込み String。

**戻り値:**
java.lang.String

### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

感度ラベルの ID を取得または設定します。 読み取り/書き込み String。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```

感度ラベルを説明する感度ラベル ポリシーに対応する Azure Active Directory (Azure AD) サイト識別子を取得または設定します。 読み取り/書き込み java.util.UUID。

**戻り値:**
java.util.UUID

### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```

感度ラベルを説明する感度ラベル ポリシーに対応する Azure Active Directory (Azure AD) サイト識別子を取得または設定します。 読み取り/書き込み java.util.UUID。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```

感度ラベルが有効かどうかを示します。

**戻り値:**
boolean

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```

感度ラベルが有効かどうかを示します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```

感度ラベルが削除されたかどうかを示します。

**戻り値:**
boolean

### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```

感度ラベルが削除されたかどうかを示します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```

感度ラベルの割り当て方法を取得または設定します。 読み取り/書き込み [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype)。

**戻り値:**
int

### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```

感度ラベルの割り当て方法を取得または設定します。 読み取り/書き込み [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype)。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

ファイルに適用すべきコンテンツ マーキングのタイプの一覧を取得します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - コンテンツタイプのリスト [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)