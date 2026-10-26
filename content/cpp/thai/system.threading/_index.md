---
title: "System::Threading"
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 1002
url: /th/system.threading/
---
## คลาส

| คลาส | คำอธิบาย |
| --- | --- |
| [AutoResetEvent](./autoresetevent/) | เหตุการณ์เพื่อแจ้งเตือนเธรดที่กำลังรอซึ่งรีเซ็ตอัตโนมัติ. วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ห่อหุ้มคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../system/smartptr/) เสมอและใช้ตัวชี้นี้เพื่อส่งไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [CancellationToken](./cancellationtoken/) | กระจายการแจ้งเตือนว่าการดำเนินการควรยกเลิก. คลาสนี้ให้กลไกสำหรับการยกเลิกแบบร่วมมือระหว่างเธรด, โดยทำให้เธรดหนึ่งสามารถแจ้งให้เธรดอื่นทราบว่าการดำเนินการควรยกเลิก. |
| [CancellationTokenRegistration](./cancellationtokenregistration/) | เป็นการลงทะเบียนสำหรับการเรียกคืนโทเคนการยกเลิก. |
| [CancellationTokenSource](./cancellationtokensource/) | แหล่งโทเคนการยกเลิกที่สามารถใช้เพื่อกระตุ้นการแจ้งเตือนการยกเลิก. |
| [Details_SemaphoreFullException](./details_semaphorefullexception/) |  |
| [Details_SynchronizationLockException](./details_synchronizationlockexception/) |  |
| [Details_ThreadAbortException](./details_threadabortexception/) |  |
| [Details_ThreadInterruptedException](./details_threadinterruptedexception/) |  |
| [Details_ThreadStateException](./details_threadstateexception/) |  |
| [EventWaitHandle](./eventwaithandle/) | เหตุการณ์ที่สามารถส่งไปยังเธรดที่กำลังรอ. วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ห่อหุ้มคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../system/smartptr/) เสมอและใช้ตัวชี้นี้เพื่อส่งไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [Interlocked](./interlocked/) | ให้ API สำหรับการดำเนินการที่ปลอดภัยต่อเธรด. นี้เป็นประเภทแบบสแตติกที่ไม่มีบริการอินสแตนซ์. คุณไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใด ๆ. |
| [ManualResetEvent](./manualresetevent/) | เหตุการณ์เพื่อแจ้งเตือนเธรดที่กำลังรอซึ่งไม่รีเซ็ตอัตโนมัติ. วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ห่อหุ้มคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../system/smartptr/) เสมอและใช้ตัวชี้นี้เพื่อส่งไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [Monitor](./monitor/) | คลาส [Monitor](./monitor/) ให้กลไกที่ทำการประสานการเข้าถึงวัตถุ. |
| [Mutex](./mutex/) | การดำเนินการ [Mutex](./mutex/). วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ห่อหุ้มคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../system/smartptr/) เสมอและใช้ตัวชี้นี้เพื่อส่งไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [Semaphore](./semaphore/) | การดำเนินการ [Semaphore](./semaphore/). วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ห่อหุ้มคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../system/smartptr/) เสมอและใช้ตัวชี้นี้เพื่อส่งไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [SynchronizationContext](./synchronizationcontext/) | ให้ฟังก์ชันพื้นฐานสำหรับการกระจายบริบทการซิงโครไนซ์ผ่านการดำเนินการซิงโครไนซ์ต่าง ๆ. |
| [Thread](./thread/) | การดำเนินการ [Thread](./thread/). วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ห่อหุ้มคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../system/smartptr/) เสมอและใช้ตัวชี้นี้เพื่อส่งไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [ThreadPool](./threadpool/) | API ของ pool [Thread](./thread/) ที่อนุญาตให้ผลักงานเข้าสู่คิวเพื่อให้ pool ของเธรดทำงานอ่านได้. นี้เป็นประเภทแบบสแตติกที่ไม่มีบริการอินสแตนซ์. คุณไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใด ๆ. |
| [ThreadPoolImpl](./threadpoolimpl/) | ข้อมูลภายในของ pool [Thread](./thread/). นี้เป็นประเภทแบบซิงเกิลตันที่มีการจัดการหน่วยความจำโดยฟังก์ชันการเข้าถึง. คุณไม่ควรสร้างอินสแตนซ์ของมันโดยตรง. |
| [Timer](./timer/) | คลาส [Timer](./timer/) ที่ดำเนินการงานในเธรดแยกหลังจากดีเลย์. วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ห่อหุ้มคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../system/smartptr/) เสมอและใช้ตัวชี้นี้เพื่อส่งไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [TimerQueue](./timerqueue/) | คิวที่จัดการวัตถุ [Timer](./timer/). นี้เป็นเพียงการดำเนินการ. วัตถุ [Timer](./timer/) ลงทะเบียนเองที่นี่, คุณไม่จำเป็นต้องทำเช่นนั้นเพื่อใช้พวกมัน - ใช้ API ของคลาส [Timer](./timer/) แทน. นี้เป็นประเภทแบบซิงเกิลตันที่มีการจัดการหน่วยความจำโดยฟังก์ชันการเข้าถึง. คุณไม่ควรสร้างอินสแตนซ์ของมันโดยตรง. |
| [WaitHandle](./waithandle/) | คลาสฐานของ primitive ที่ใช้รอ. วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ห่อหุ้มคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../system/smartptr/) เสมอและใช้ตัวชี้นี้เพื่อส่งไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |

## โครงสร้าง

| โครงสร้าง | คำอธิบาย |
| --- | --- |
| [Timeout](./timeout/) | ค่าเวลาจำกัดพิเศษของ [Threading](./). นี้เป็นประเภทแบบสแตติกที่ไม่มีบริการอินสแตนซ์. คุณไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใด ๆ. |

## เอนัม

| เอนัม | คำอธิบาย |
| --- | --- |
| [ApartmentState](./apartmentstate/) | กำหนดสถานะ apartment ของเธรด. |
| [EventResetMode](./eventresetmode/) | ระบุว่ารัฐของเหตุการณ์รีเซ็ตอย่างไร. |
| [ThreadState](./threadstate/) | สถานะของเธรด. |

## ประเภทนิยาม

| ประเภทนิยาม | คำอธิบาย |
| --- | --- |
| [ThreadStateException](./threadstateexception/) |  |
| [SemaphoreFullException](./semaphorefullexception/) |  |
| [SynchronizationLockException](./synchronizationlockexception/) |  |
| [ThreadAbortException](./threadabortexception/) |  |
| [ThreadInterruptedException](./threadinterruptedexception/) |  |
| [SendOrPostCallback](./sendorpostcallback/) |  |
| [ParameterizedThreadStart](./parameterizedthreadstart/) | ฟังก์ชัน [Thread](./thread/) ที่มีพารามิเตอร์เดียว. |
| [ThreadStart](./threadstart/) | ฟังก์ชัน [Thread](./thread/) ที่ไม่มีพารามิเตอร์. |
| [WaitCallback](./waitcallback/) | รายการ callback ที่จะดำเนินการเมื่อมีตำแหน่งว่าง. |
| [TimerCallback](./timercallback/) | ฟังก์ชัน callback ที่จะถูกเรียกโดยตัวจับเวลา. |
| [wait_handle_t](./wait_handle_t/) | ประเภทตัวจัดการ. |