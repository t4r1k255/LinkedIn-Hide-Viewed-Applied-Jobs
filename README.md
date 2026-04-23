# LinkedIn Jobs Fast

LinkedIn iş arama sayfasında görüntülenen ve başvurulan ilanları gizleyen, sayfayı hızlandıran Tampermonkey/Violentmonkey scripti.

---

## Özellikler

- Görüntülenen ilanları gizleme
- Başvurulan ilanları gizleme
- Her iki filtre birbirinden bağımsız açılıp kapatılabilir
- Performans modu: animasyonları kapatır, RAM ve CPU kullanımını düşürür
- Ayarlar kaydedilir, sayfa yenilenince hatırlanır
- Yalnızca `/jobs` sayfalarında etkinleşir

---

## Kurulum

1. Tarayıcına [Tampermonkey](https://www.tampermonkey.net/) ya da [Violentmonkey](https://violentmonkey.github.io/) eklentisini yükle.
2. [linkedin-jobs-fast.user.js](./linkedin-jobs-fast.user.js) dosyasını aç.
3. Eklentinin kontrol panelinde **Yeni Script Ekle**'ye tıkla, içeriği yapıştır ve kaydet.
4. LinkedIn'i yenile.

**Uyumluluk:** Chrome · Edge · Firefox

---

## Kullanım

LinkedIn'de `/jobs` sayfasına girdiğinde sağ üst köşede küçük bir panel belirir.

| Buton | Açıklama |
|---|---|
| **Görüntülenen** | Daha önce tıkladığın ilanları gizler · Tekrar tıklayınca gösterir |
| **Başvurulan** | Başvurduğun ilanları gizler · Tekrar tıklayınca gösterir |
| **⚡ Hız** | Performans modunu açar/kapatır |

Panelin solundaki sayı o an kaç ilanın gizlendiğini gösterir.

---

## Lisans

MIT
