# VEAcom eki: ekran kartı olmadan çizim

VEAcom **"Bu bilgisayarın ekran kartı görüntüleri çizmeye yetmiyor"** diyorsa bu eki kurun.
Uzak masaüstüyle bağlanılan, eski ya da ekran kartı sürücüsü olmayan bilgisayarlarda gerekir.

**[veacom-ek.zip dosyasını indir](https://github.com/sekerportakal/veacom-releases/raw/main/veacom-ek.zip)** (22 MB)

1. VEAcom'u kapatın.
2. `veacom-ek.zip` dosyasını açın (sağ tık → Tümünü ayıkla).
3. Çıkan klasördeki `kur.bat` dosyasına çift tıklayın.

Görüntüler ekran kartı olmadan, işlemciyle çizilir. Görüntüler aynıdır; kaydırma biraz, 3D belirgin şekilde yavaşlar.
VEAcom güncellendiğinde yeniden kurmanız gerekmez.

Kaldırmak için: VEAcom.exe'nin yanındaki `opengl32.dll` ve `libgallium_wgl.dll` dosyalarını silin.

İçinde Mesa 26.2.5 bulunur (MIT lisansı; ayrıntılar zip içindeki `MESA-LISANS.txt` dosyasında).
