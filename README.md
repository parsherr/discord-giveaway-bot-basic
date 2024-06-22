# Discord.js v13 Giveaway bot

prefix ile çalışan gayet güzel bir çekiliş botu, express.js eklenmiştir eğer site yapmak isterseniz vs. diye ve ayrıca slash handlerleri eklenip /slash komutları için klasör ayarlanmıştır yani dilerseniz pek uğraşmadan / komutlarıda ekleyebilirsiniz 


## Kurulum
1. **Ayarlar Dosyasını Düzenleyin:**
    - `config.js` dosyasını açın ve aşağıdaki alanları kendi bilgilerinizle doldurun:
    ```js
    {
    "token" : "", // botunuzun tokeni zorunlu
    "prefix": ".", // bot prefixi zorunlu
    "everyoneMention": true, // opsiyonel
    "showMention": true, // opsiyonel
    "hostedBy": true // opsiyonel
    }

    ```

    
2. **Gerekli Paketleri Yükleyin:**
    - Proje dizininde terminali açın ve aşağıdaki komutu çalıştırın:
    ```bash
    npm i
    pnpm i
    ```
3. **Botu Başlatın:**
    - `node .` ve ya `node parsher.js` ile dosyasını çalıştırın.


## Destek

Herhangi bir sorunla karşılaşırsanız veya yardım almak isterseniz:

[![Discord Banner](https://api.weblutions.com/discord/invite/bdfd/)](https://discord.gg/bdfd)

---

# Başlat.bat yapımı :
- aşağadaki kodu kopyalayıp "start.bat" isimli bi dosya açın, kopyaladığınız metni bat dosyasına girin.
    ```bash
    echo off
    color 0f
    cls
    :a
    node index.js
    goto a
    ```

    iyi kullanımlar