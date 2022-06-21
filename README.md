# UC-Flutter-cw-5

## تمرين 1
احد المدارس تعاني من بطئ عملية رصد تقديرات (A,B,C,D,F) الطلاب لذى المطلوب منا مساعدتهم بحيث نصنع لهم برنامج ياخذ درجة الطلاب و يرجع التقدير

1. قم بعمل fork للـ repository
2. افتح الـ repository باستخدام github desktop
3. ادخل على برنامج VS code   وانشاء ملف تمرين داخل مجلد cw-1 في ال repository
4.  قم بإنشاء برنامج Flutter جديد و احفظه داخل الملف
5. أضف MatiralApp  و Scofield للبرنامج
6. اضف دالة تقوم بعملية تحويل الدرجة الى تقدير في المكان المناسب بالبرنامج
7. ثم اضف Column widget و بداخلها textfield widget , button widget , text widget
8. في Textfield widget  اضف controller  وقم بالتعديلات اللازمة على البرنامج



hints:
مطلوب استخدام 
ٍ  
* stateful widget
* TextField widget
* Button widget 
* Text widget
* function  تقوم باخذ الدرجة و اعادتها كتقدير للطلاب



<img src="images/Grade.jpg" height="300"/>



_____________________________________________________________________________________________________________



## تمرين 2
في هذا الجزء أرادت المدرسة  باضافة المزيد من التعديلات وبحيث نضيف model للبرنامج لكي يحفظ بيانات الطلاب ويسهل عمل التطويرات المستقبلية في البرنامج و يحتوي على :
1. نكمل على التمرين السابقة 
2. إنشاء مجلد models داخل مجلد Lib
3. قم بإضافة ملف باسم Student.dart
4. قم بإضافة التالي:

```
int id
String studentName
double studentMark
int studentAge
```
5. ثم اضف constructor لهم 
