---
title: IsCppContainer
second_title: Aspose.Slides for C++ API 參考
description: "檢查特定類型是否為 STL 風格的容器。為此，檢查 iterator 與 const_iterator 成員型別是否存在。若兩者皆存在，繼承 std::true_type；否則繼承 std::false_type。"
type: docs
weight: 40
url: /zh-hant/system.testpredicates.typetraits/iscppcontainer/
---
## IsCppContainer struct

檢查特定類型是否為 STL 風格的容器。為此，檢查是否存在 iterator 與 const_iterator 成員型別。若兩者皆存在，繼承 std::true_type；否則繼承 std::false_type。

```cpp
template<typename T,typename Enable>class IsCppContainer : public std::false_type
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 要檢查的類型。 |
| Enable | 用於使 SFINAE 生效的形式參數。 |

## 另請參閱

* 命名空間 [System::TestPredicates::TypeTraits](../)
* 函式庫 [Aspose.Slides](../../)