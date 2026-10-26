---
title: Remove()
second_title: Aspose.Slides C++용 API 참조
description: ICollection에서 특정 객체의 첫 번째 발생을 제거합니다.
type: docs
weight: 339
url: /ko/aspose.slides.effects/imagetransformoperationcollection/remove/
---
## ImageTransformOperationCollection::Remove(const System::SharedPtr\<IImageTransformOperation\>\&) 메서드


특정 객체를 [ICollection](../../../system.collections.generic/icollection/)에서 첫 번째로 나타나는 것을 제거합니다.

```cpp
bool Aspose::Slides::Effects::ImageTransformOperationCollection::Remove(const System::SharedPtr<IImageTransformOperation> &item) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IImageTransformOperation](../../iimagetransformoperation/)\>\& | [ICollection](../../../system.collections.generic/icollection/)에서 제거할 객체. |

### 반환 값

*item*이 [ICollection](../../../system.collections.generic/icollection/)에서 성공적으로 제거되면 true; 그렇지 않으면 false. 이 메서드는 *item*이 원래 [ICollection](../../../system.collections.generic/icollection/)에 없을 경우에도 false를 반환합니다.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IImageTransformOperation](../../iimagetransformoperation/)
* 클래스 [ImageTransformOperationCollection](../)
* 네임스페이스 [Aspose::Slides::Effects](../../)
* 라이브러리 [Aspose.Slides](../../../)