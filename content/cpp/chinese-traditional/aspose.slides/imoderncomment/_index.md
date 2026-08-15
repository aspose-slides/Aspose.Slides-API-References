---
title: IModernComment
second_title: Aspose.Slides for C++ API 參考
description: 表示投影片上的註解。
type: docs
weight: 2965
url: /zh-hant/aspose.slides/imoderncomment/
---
## IModernComment 類別


表示投影片上的註解。

```cpp
class IModernComment : public virtual Aspose::Slides::IComment
```

## 方法

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 在 C# 風格中比較參考類型物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 在 C# 風格中比較值類型物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_Author](../icomment/get_author/)() | 傳回註解的作者。唯讀 [ICommentAuthor](../icommentauthor/)。 |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](../icomment/get_createdtime/)() | 傳回註解建立的時間。將此屬性設為 [DateTime::MinValue](../../system/datetime/minvalue/) 表示未設定註解時間。唯讀 [System::DateTime](../../system/datetime/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\> [get_ParentComment](../icomment/get_parentcomment/)() | 取得父註解。唯讀 [IComment](../icomment/)。 |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_Position](../icomment/get_position/)() | 傳回註解在投影片上的位置。唯讀 [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)() | 傳回與註解關聯的圖形。唯讀 [IShape](../ishape/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](../icomment/get_slide/)() | 傳回註解的父投影片。唯讀 [ISlide](../islide/)。 |
| virtual [ModernCommentStatus](../moderncommentstatus/) [get_Status](./get_status/)() | 傳回註解的狀態。唯讀 [ModernCommentStatus](../moderncommentstatus/)。 |
| virtual [System::String](../../system/string/) [get_Text](../icomment/get_text/)() | 傳回投影片註解的純文字。唯讀 [System::String](../../system/string/)。 |
| virtual **int32_t** [get_TextSelectionLength](./get_textselectionlength/)() | 如果註解與 [AutoShape](../autoshape/) 相關聯，傳回文字框中選取的長度。唯讀 **int32_t**。 |
| virtual **int32_t** [get_TextSelectionStart](./get_textselectionstart/)() | 如果註解與 [AutoShape](../autoshape/) 相關聯，傳回文字框中選取的起始位置。唯讀 **int32_t**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構子。實際上不會拷貝任何東西，只是初始化新物件並允許子類別進行拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會拷貝任何東西，只是初始化新物件並允許子類別進行拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值類型物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，用於字串的情況。 |
| virtual void [Remove](../icomment/remove/)() | 從父集合中移除註解及其所有回覆。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [set_CreatedTime](../icomment/set_createdtime/)([System::DateTime](../../system/datetime/)) | 設定註解建立的時間。將此屬性設為 [DateTime::MinValue](../../system/datetime/minvalue/) 表示未設定註解時間。寫入 [System::DateTime](../../system/datetime/)。 |
| virtual void [set_ParentComment](../icomment/set_parentcomment/)([System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>) | 設定父註解。寫入 [IComment](../icomment/)。 |
| virtual void [set_Position](../icomment/set_position/)([System::Drawing::PointF](../../system.drawing/pointf/)) | 設定註解在投影片上的位置。寫入 [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| virtual void [set_Status](./set_status/)([ModernCommentStatus](../moderncommentstatus/)) | 設定註解的狀態。寫入 [ModernCommentStatus](../moderncommentstatus/)。 |
| virtual void [set_Text](../icomment/set_text/)([System::String](../../system/string/)) | 設定投影片註解的純文字。寫入 [System::String](../../system/string/)。 |
| virtual void [set_TextSelectionLength](./set_textselectionlength/)(**int32_t**) | 如果註解與 [AutoShape](../autoshape/) 相關聯，設定文字框中選取的長度。寫入 **int32_t**。 |
| virtual void [set_TextSelectionStart](./set_textselectionstart/)(**int32_t**) | 如果註解與 [AutoShape](../autoshape/) 相關聯，設定文字框中選取的起始位置。寫入 **int32_t**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。 不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。 不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解除鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。 不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。 不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |
## 備註



```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
auto modernComment = newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```




## 另請參閱

* 類別 [IComment](../icomment/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)