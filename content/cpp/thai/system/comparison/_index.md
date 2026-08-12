---
title: Comparison
second_title: "อ้างอิง API ของ Aspose.Slides สำหรับ C++"
description: "เป็นตัวชี้ไปยังเมธอดที่เปรียบเทียบอ็อบเจกต์สองอันที่มีชนิดเดียวกัน ประเภทนี้ควรจัดสรรบนสแตกและส่งผ่านไปยังฟังก์ชันโดยค่าหรือโดยอ้างอิง ไม่ควรใช้คลาส System::SmartPtr เพื่อจัดการอ็อบเจกต์ประเภทนี้"
type: docs
weight: 183
url: /th/system/comparison/
---
## คลาสการเปรียบเทียบ


เป็นตัวชี้ไปยังเมธอดที่เปรียบเทียบอ็อบเจกต์สองอันที่มีชนิดเดียวกัน ประเภทนี้ควรจัดสรรบนสแตกและส่งผ่านไปยังฟังก์ชันโดยค่าหรือโดยอ้างอิง ไม่ควรใช้คลาส [System::SmartPtr](../smartptr/) เพื่อจัดการอ็อบเจกต์ประเภทนี้

```cpp
template<typename T>class Comparison : public System::MulticastDelegate<int(T, T)>
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของอ็อบเจกต์ที่เมธอดเปรียบเทียบ |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| **bool** [operator()](./operator_call/)(T, T) | เรียกใช้อ็อบเจกต์ที่สามารถเรียกได้ซึ่งชี้โดยอ็อบเจกต์ปัจจุบัน |
## หมายเหตุ



```cpp
#include "system/comparison.h"
#include "system/console.h"
#include "system/exceptions.h"
#include "system/string.h"
#include <algorithm>
#include <initializer_list>
#include <vector>

using namespace System;

// คลาสเทมเพลตที่เป็นตัวแทนของอาร์เรย์แบบไดนามิก.
template <typename T>
class MyArray
{
  // ใชเพื่อเก็บข้อมูลของอาร์เรย์.
  std::vector<T> m_data;

public:
  // สร้างอินสแตนซ์ใหม่ของอาร์เรย์ไดนามิกของเรา.
  MyArray(const std::initializer_list<T>& source) : m_data(source) {};

  // ใชเพื่อจัดเรียงข้อมูลของอาร์เรย์ เมธอดนี้รับอินสแตนซ์ของ
  // คลาสเทมเพลต 'System::Comparison'.
  void Sort(Comparison<T> comparison)
  {
    if (comparison.IsNull())
    {
      throw ArgumentNullException(u"comparison");
    }
    std::sort(m_data.begin(), m_data.end(), comparison);
  }

  // คืนค่าจำนวนขององค์ประกอบที่อาร์เรย์ไดนามิกของเราจัดเก็บ.
  size_t get_Size()
  {
    return m_data.size();
  }

  // ใชเพื่อดึงองค์ประกอบที่ตำแหน่งเฉพาะ.
  T& operator[](int index)
  {
    if (index < 0 || index >= m_data.size())
    {
      throw IndexOutOfRangeException(u"index");
    }
    return m_data[index];
  }
};

int main() {
  // สร้างอินสแตนซ์ของคลาส MyArray ด้วยองค์ประกอบที่ระบุ.
  MyArray<String> arr = {u"a", u"e", u"c", u"b", u"d"};

  // จัดเรียงตามลำดับเพิ่มขององค์ประกอบในอาร์เรย์ไดนามิก.
  arr.Sort([](const String &a, const String &b) -> int
  {
    return String::Compare(a, b);
  });

  // พิมพ์องค์ประกอบของอาร์เรย์ไดนามิก.
  for (auto i = 0; i < arr.get_Size(); ++i)
  {
    Console::WriteLine(arr[i]);
  }

  return 0;
}
/*
ตัวอย่างโค้ดนี้จะสร้างผลลัพธ์ต่อไปนี้:
a
b
c
d
e
*/
```

## ดูเพิ่มเติม

* เนมส페ซ [System](../)
* ไลบรารี [Aspose.Slides](../../)