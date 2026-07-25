---
title: Comment
second_title: Aspose.Slides for C++ API リファレンス
description: スライド上のコメントを表します。
type: docs
weight: 417
url: /ja/aspose.slides/comment/
---
## コメント クラス


スライド上のコメントを表します。

```cpp
class Comment : public virtual Aspose::Slides::IComment,
                public Aspose::Slides::IDOMObject
```

## メソッド

| Method | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、ここでは 2 つの NaN が等しいとみなされます。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、ここでは 2 つの NaN が等しいとみなされます。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部目的専用です。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_Author](./get_author/)() override | コメントの作成者を返します。読み取り専用 [ICommentAuthor](../icommentauthor/)。 |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | コメント作成時刻を返します。このプロパティを [DateTime::MinValue](../../system/datetime/minvalue/) に設定するとコメント時刻が設定されていないことを意味します。読み取り [System::DateTime](../../system/datetime/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\> [get_ParentComment](./get_parentcomment/)() override | 親コメントを取得します。読み取り [IComment](../icomment/)。 |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_Position](./get_position/)() override | スライド上のコメントの位置を返します。読み取り [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](./get_slide/)() override | コメントの親スライドを返します。読み取り専用 [ISlide](../islide/)。 |
| [System::String](../../system/string/) [get_Text](./get_text/)() override | スライドコメントのプレーンテキストを返します。読み取り [System::String](../../system/string/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列のケースに対する特殊化です。 |
| void [Remove](./remove/)() override | コメントとそのすべての返信を親コレクションから削除します。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 共有参照カウントを指定された値だけ減少させます。 |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | コメント作成時刻を設定します。このプロパティを [DateTime::MinValue](../../system/datetime/minvalue/) に設定するとコメント時刻が設定されていないことを意味します。書き込み [System::DateTime](../../system/datetime/)。 |
| void [set_ParentComment](./set_parentcomment/)([System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>) override | 親コメントを設定します。書き込み [IComment](../icomment/)。 |
| void [set_Position](./set_position/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | スライド上のコメントの位置を設定します。書き込み [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| void [set_Text](./set_text/)([System::String](../../system/string/)) override | スライドコメントのプレーンテキストを設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 備考


この例は、PowerPoint プレゼンテーションのスライドにコメントを追加する方法を示しています。 
```cpp
// Presentation クラスのインスタンスを作成します
auto presentation = System::MakeObject<Presentation>();

// 空のスライドを追加します
presentation->get_Slides()->AddEmptySlide(presentation->get_LayoutSlides()->idx_get(0));
// 作者を追加します
auto author = presentation->get_CommentAuthors()->AddAuthor(u"Jawad", u"MF");
// コメントの位置を設定します
System::Drawing::PointF point(0.2f, 0.2f);
// スライド 1 の作者に対してスライドコメントを追加します
author->get_Comments()->AddComment(u"Hello Jawad, this is slide comment", presentation->get_Slides()->idx_get(0), point, System::DateTime::get_Now());
// スライド 2 の作者に対してスライドコメントを追加します
author->get_Comments()->AddComment(u"Hello Jawad, this is second slide comment", presentation->get_Slides()->idx_get(1), point, System::DateTime::get_Now());
// PowerPoint プレゼンテーション ファイルを保存します
presentation->Save(u"Comments_out.pptx", SaveFormat::Pptx);
```
この例は、PowerPoint プレゼンテーションのスライド上の既存のコメントにアクセスする方法を示しています。 
```cpp
// Presentation クラスのインスタンスを作成します
auto presentation = System::MakeObject<Presentation>(u"Comments1.pptx");

// CommentAuthors を走査します
for (CommentAuthor&& commentAuthor : presentation->get_CommentAuthors())
{
    // Comments を走査します
    for (Comment&& comment : commentAuthor->get_Comments())
    {
        System::Console::WriteLine(System::String(u"ISlide :") + comment->get_Slide()->get_SlideNumber() +
                                   u" has comment: " + comment->get_Text() +
                                   u" with Author: " + comment->get_Author()->get_Name() +
                                   u" posted on time :" + comment->get_CreatedTime() + u"\n");
    }
}
```
この例は、コメントを追加し、それへの返信を取得する方法を示しています。 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
System::Drawing::PointF pos(10.0f, 10.0f);

// コメントを追加します
System::SharedPtr<ICommentAuthor> author1 = pres->get_CommentAuthors()->AddAuthor(u"Author_1", u"A.A.");
System::SharedPtr<IComment> comment1 = author1->get_Comments()->AddComment(u"comment1", slide, pos, System::DateTime::get_Now());
// comment1 への返信を追加します
System::SharedPtr<ICommentAuthor> author2 = pres->get_CommentAuthors()->AddAuthor(u"Autror_2", u"B.B.");
System::SharedPtr<IComment> reply1 = author2->get_Comments()->AddComment(u"reply 1 for comment 1", slide, pos, System::DateTime::get_Now());
reply1->set_ParentComment(comment1);
// comment1 に対する別の返信を追加します
System::SharedPtr<IComment> reply2 = author2->get_Comments()->AddComment(u"reply 2 for comment 1", slide, pos, System::DateTime::get_Now());
reply2->set_ParentComment(comment1);
// 既存の返信に対する返信を追加します
System::SharedPtr<IComment> subReply = author1->get_Comments()->AddComment(u"subreply 3 for reply 2", slide, pos, System::DateTime::get_Now());
subReply->set_ParentComment(reply2);
System::SharedPtr<IComment> comment2 = author2->get_Comments()->AddComment(u"comment 2", slide, pos, System::DateTime::get_Now());
System::SharedPtr<IComment> comment3 = author2->get_Comments()->AddComment(u"comment 3", slide, pos, System::DateTime::get_Now());
System::SharedPtr<IComment> reply3 = author1->get_Comments()->AddComment(u"reply 4 for comment 3", pres->get_Slides()->idx_get(0), pos, System::DateTime::get_Now());
reply3->set_ParentComment(comment3);

// コンソールにコメント階層を表示します
auto comments = slide->GetSlideComments(nullptr);
for (int32_t i = 0; i < comments->get_Length(); i++)
{
    System::SharedPtr<IComment> comment = comments[i];
    while (comment->get_ParentComment() != nullptr)
    {
        System::Console::Write(u"\t");
        comment = comment->get_ParentComment();
    }

    System::Console::Write(u"{0} : {1}", comments[i]->get_Author()->get_Name(), comments[i]->get_Text());
    System::Console::WriteLine();
}

pres->Save(u"parent_comment.pptx", SaveFormat::Pptx);
// comment1 とそれへのすべての返信を削除します
comment1->Remove();
pres->Save(u"remove_comment.pptx", SaveFormat::Pptx);
```

## 参照

* クラス [IComment](../icomment/)
* クラス [IDOMObject](../idomobject/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)