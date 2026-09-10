# [Рабочее зеркало для кинопаба](https://zerkalo.xyz)

# zerkalo.xyz

С любыми вопросами пишите нам в support@kino.pub и мы поможем!

## Сертификаты для приставок

- `usertrust_ecc_root.pem` — корневой USERTrust ECC. Нужен ATV3 для видео с CDN
  (цепочка ZeroSSL → Sectigo E46 → USERTrust ECC). Ставится **дополнительно** к ISRG Root X1,
  не вместо: ISRG отвечает за microiptv.org, без него отвалится авторизация.
  Срок до 18.01.2038, SHA-256 4F:F4:60:D5:4B:9C:86:DA:BF:BC:FC:57:12:E0:40:0D:2B:ED:3F:BC:4D:4F:BD:AA:86:E0:6A:DC:D2:A9:AD:7A
