---
title: IVbaModuleCollection
second_title: Aspose.Slides for Java API リファレンス
description: VBA プロジェクト モジュールのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/ivbamodulecollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

VBA プロジェクト モジュールのコレクションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | VBA プロジェクトに新しい空のモジュールを追加します。 |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | コレクションから特定のオブジェクトの最初の出現を削除します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```

指定されたインデックスの要素を取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```

VBA プロジェクトに新しい空のモジュールを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | モジュールの名前 |

**戻り値:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - 追加されたモジュール。
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```

コレクションから特定のオブジェクトの最初の出現を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | コレクションから削除するモジュール。 |