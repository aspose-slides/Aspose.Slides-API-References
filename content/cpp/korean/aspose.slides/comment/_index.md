---
title: Comment
second_title: Aspose.Slides for C++ API 레퍼런스
description: 슬라이드에 대한 주석을 나타냅니다.
type: docs
weight: 417
url: /ko/aspose.slides/comment/
---
## Comment 클래스

슬라이드에 대한 주석을 나타냅니다.

```cpp
class Comment : public virtual Aspose::Slides::IComment,
                public Aspose::Slides::IDOMObject
```

## Methods

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# 스타일의 부동 소수점 비교를 에뮬레이트합니다. 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도( NaN 자체 포함) 같지 않음에도 불구하고 동일하다고 간주됩니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# 스타일의 부동 소수점 비교를 에뮬레이트합니다. 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도( NaN 자체 포함) 같지 않음에도 불구하고 동일하다고 간주됩니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부용도 전용입니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_Author](./get_author/)() override | 주석의 작성자를 반환합니다. 읽기 전용 [ICommentAuthor](../icommentauthor/). |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | 주석 생성 시간을 반환합니다. 이 속성을 [DateTime::MinValue](../../system/datetime/minvalue/)(으)로 설정하면 주석 시간이 설정되지 않은 것입니다. 읽기 [System::DateTime](../../system/datetime/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\> [get_ParentComment](./get_parentcomment/)() override | 부모 주석을 가져옵니다. 읽기 [IComment](../icomment/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_Position](./get_position/)() override | 슬라이드에서 주석의 위치를 반환합니다. 읽기 [System::Drawing::PointF](../../system.drawing/pointf/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](./get_slide/)() override | 주석의 부모 슬라이드를 반환합니다. 읽기 전용 [ISlide](../islide/). |
| [System::String](../../system/string/) [get_Text](./get_text/)() override | 슬라이드 주석의 일반 텍스트를 반환합니다. 읽기 [System::String](../../system/string/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스의 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스의 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| void [Remove](./remove/)() override | 주석 및 해당 모든 답글을 부모 컬렉션에서 제거합니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | 주석 생성 시간을 설정합니다. 이 속성을 [DateTime::MinValue](../../system/datetime/minvalue/)(으)로 설정하면 주석 시간이 설정되지 않은 것입니다. 쓰기 [System::DateTime](../../system/datetime/). |
| void [set_ParentComment](./set_parentcomment/)([System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>) override | 부모 주석을 설정합니다. 쓰기 [IComment](../icomment/). |
| void [set_Position](./set_position/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | 슬라이드에서 주석의 위치를 설정합니다. 쓰기 [System::Drawing::PointF](../../system.drawing/pointf/). |
| void [set_Text](./set_text/)([System::String](../../system/string/)) override | 슬라이드 주석의 일반 텍스트를 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 레퍼런스 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 비고

이 예제는 PowerPoint 프레젠테이션의 슬라이드에 주석을 추가하는 방법을 보여줍니다.  
```cpp
// Presentation 클래스 인스턴스화
auto presentation = System::MakeObject<Presentation>();

// 빈 슬라이드 추가
presentation->get_Slides()->AddEmptySlide(presentation->get_LayoutSlides()->idx_get(0));
// 작성자 추가
auto author = presentation->get_CommentAuthors()->AddAuthor(u"Jawad", u"MF");
// 주석 위치 설정
System::Drawing::PointF point(0.2f, 0.2f);
// 슬라이드 1에 작성자의 슬라이드 주석 추가
author->get_Comments()->AddComment(u"Hello Jawad, this is slide comment", presentation->get_Slides()->idx_get(0), point, System::DateTime::get_Now());
// 슬라이드 2에 작성자의 슬라이드 주석 추가
author->get_Comments()->AddComment(u"Hello Jawad, this is second slide comment", presentation->get_Slides()->idx_get(1), point, System::DateTime::get_Now());
// PowerPoint 프레젠테이션 파일 저장
presentation->Save(u"Comments_out.pptx", SaveFormat::Pptx);
```
이 예제는 PowerPoint 프레젠테이션의 슬라이드에 있는 기존 주석에 접근하는 방법을 보여줍니다.  
```cpp
// Presentation 클래스를 인스턴스화
auto presentation = System::MakeObject<Presentation>(u"Comments1.pptx");

// Iterate CommentAuthors
for (CommentAuthor&& commentAuthor : presentation->get_CommentAuthors())
{
    // Comments 반복
    for (Comment&& comment : commentAuthor->get_Comments())
    {
        System::Console::WriteLine(System::String(u"ISlide :") + comment->get_Slide()->get_SlideNumber() +
                                   u" has comment: " + comment->get_Text() +
                                   u" with Author: " + comment->get_Author()->get_Name() +
                                   u" posted on time :" + comment->get_CreatedTime() + u"\n");
    }
}
```
이 예제는 주석을 추가하고 해당 주석에 대한 답글을 얻는 방법을 보여줍니다.  
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
System::Drawing::PointF pos(10.0f, 10.0f);

// 주석 추가
System::SharedPtr<ICommentAuthor> author1 = pres->get_CommentAuthors()->AddAuthor(u"Author_1", u"A.A.");
System::SharedPtr<IComment> comment1 = author1->get_Comments()->AddComment(u"comment1", slide, pos, System::DateTime::get_Now());
// comment1에 대한 답글 추가
System::SharedPtr<ICommentAuthor> author2 = pres->get_CommentAuthors()->AddAuthor(u"Autror_2", u"B.B.");
System::SharedPtr<IComment> reply1 = author2->get_Comments()->AddComment(u"reply 1 for comment 1", slide, pos, System::DateTime::get_Now());
reply1->set_ParentComment(comment1);
// comment1에 대한 또 다른 답글 추가
System::SharedPtr<IComment> reply2 = author2->get_Comments()->AddComment(u"reply 2 for comment 1", slide, pos, System::DateTime::get_Now());
reply2->set_ParentComment(comment1);
// 기존 답글에 대한 답글 추가
System::SharedPtr<IComment> subReply = author1->get_Comments()->AddComment(u"subreply 3 for reply 2", slide, pos, System::DateTime::get_Now());
subReply->set_ParentComment(reply2);
System::SharedPtr<IComment> comment2 = author2->get_Comments()->AddComment(u"comment 2", slide, pos, System::DateTime::get_Now());
System::SharedPtr<IComment> comment3 = author2->get_Comments()->AddComment(u"comment 3", slide, pos, System::DateTime::get_Now());
System::SharedPtr<IComment> reply3 = author1->get_Comments()->AddComment(u"reply 4 for comment 3", pres->get_Slides()->idx_get(0), pos, System::DateTime::get_Now());
reply3->set_ParentComment(comment3);

// 콘솔에 주석 계층 구조 표시
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
// comment1 및 해당 모든 답글 삭제
comment1->Remove();
pres->Save(u"remove_comment.pptx", SaveFormat::Pptx);
```

## 참조

* 클래스 [IComment](../icomment/)
* 클래스 [IDOMObject](../idomobject/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)