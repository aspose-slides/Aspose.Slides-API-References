---
title: IBulletFormat class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ibulletformat/
---
## IBulletFormat 類別

表示段落項目符號格式屬性。

IBulletFormat 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`type`](/slides/python-net/zh-hant/aspose.slides/ibulletformat/type/) | 取得或設定段落的項目符號類型（不含繼承）。<br/>            讀/寫 [`BulletType`](/slides/python-net/zh-hant/aspose.slides/bullettype). |
| [`char`](/slides/python-net/zh-hant/aspose.slides/ibulletformat/char/) | 取得或設定段落的項目符號字元（不含繼承）。<br/>            讀/寫 **System.Char**. |
| [`font`](/slides/python-net/zh-hant/aspose.slides/ibulletformat/font/) | 取得或設定段落的項目符號字型（不含繼承）。<br/>            讀/寫 [`IFontData`](/slides/python-net/zh-hant/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/zh-hant/aspose.slides/ibulletformat/height/) | 取得或設定段落的項目符號高度（不含繼承）。<br/>            值 float.NaN 表示項目符號會從段落的第一個區段繼承高度。<br/>            讀/寫 **float**. |
| [`color`](/slides/python-net/zh-hant/aspose.slides/ibulletformat/color/) | 取得段落的項目符號顏色格式（不含繼承）。<br/>            唯讀 [`IColorFormat`](/slides/python-net/zh-hant/aspose.slides/icolorformat). |
| [`picture`](/slides/python-net/zh-hant/aspose.slides/ibulletformat/picture/) | 取得段落中作為項目符號使用的圖片（不含繼承）。<br/>            唯讀 [`ISlidesPicture`](/slides/python-net/zh-hant/aspose.slides/islidespicture). |
| [`numbered_bullet_start_with`](/slides/python-net/zh-hant/aspose.slides/ibulletformat/numbered_bullet_start_with/) | 取得或設定編號項目符號群組使用的第一個號碼（不含繼承）。<br/>            讀/寫 **int**. |
| [`numbered_bullet_style`](/slides/python-net/zh-hant/aspose.slides/ibulletformat/numbered_bullet_style/) | 取得或設定編號項目符號的樣式（不含繼承）。<br/>            讀/寫 [`IBulletFormat.numbered_bullet_style`](/slides/python-net/zh-hant/aspose.slides/ibulletformat/numbered_bullet_style). |
| [`is_bullet_hard_color`](/slides/python-net/zh-hant/aspose.slides/ibulletformat/is_bullet_hard_color/) | 判斷項目符號是否具有自訂顏色，或從段落的第一個區段繼承顏色。<br/>            **NullableBool.True**  若項目符號具有自訂顏色，且 **NullableBool.False**  若項目符號從段落的第一個區段繼承顏色。<br/>            讀/寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/zh-hant/aspose.slides/ibulletformat/is_bullet_hard_font/) | 判斷項目符號是否具有自訂字型，或從段落的第一個區段繼承字型。<br/>            **NullableBool.True**  若項目符號具有自訂字型，且 **NullableBool.False**  若項目符號從段落的第一個區段繼承字型。<br/>            讀/寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool). |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/zh-hant/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/#) | 在啟用項目符號時（如 PowerPoint 在啟用段落項目符號/編號時的做法），為有效段落的 Indent 和 MarginLeft 設定預設的非零位移；若停用項目符號，則僅重置段落的 Indent 和 MarginLeft（如 PowerPoint 在停用段落項目符號/編號時的做法）。位移會根據目前的項目符號環境 - IBulletFormat.Type、.NumberedBulletStyle 以及第一個區段的 FontHeight 進行套用。非零的位移會套用到目前段落的有效 Indent 和 MarginLeft（使結果值為局部值）。 |
| [`get_effective(self)`](/slides/python-net/zh-hant/aspose.slides/ibulletformat/get_effective/#) | 取得套用繼承後的有效項目符號格式資料。 |

### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)