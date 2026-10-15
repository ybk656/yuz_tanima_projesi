Bu proje, Python ve OpenCV kütüphanesi kullanılarak bilgisayar kamerasından alınan canlı görüntü üzerinde gerçek zamanlı yüz tespiti yapmak amacıyla geliştirilmiştir.

Özellikler:
- Bilgisayar kamerasını (`cv2.VideoCapture(0)`) başlatır.
- `haarcascade_frontalface_default.xml` modelini kullanarak insan yüzlerini tespit eder.
- Program açıkken **"w"**tuşuna basıldığında kamerayı kapatır ve uygulamadan güvenli bir şekilde çıkar.

Gereksinimler:

Projenin bilgisayarınızda çalışabilmesi için **Python** ve **OpenCV** kütüphanesinin yüklü olması gerekmektedir.
