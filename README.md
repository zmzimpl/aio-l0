![](https://i.ibb.co/bRVhSBn/2023-06-27-00-59-28.png)
# L0 AIO by @ruburi
## Настройка софта

В файле `config.js` можно настроить софт.

- `chainsForInteractions` отвечает за список сетей, с которыми софт будет работать
- `chainsCount` отвечает за количество сетей, которые должны быть затронуты (от и до)
- `interactionsInterval` отвечает за то, сколько секунд должен быть перерыв между интеракциями (от и до)
- `interactionsCount` отвечает за то, сколько раз нужно прокрутить то или иное действие. Если хотите крутить какое-то действие бесконечно, просто выставляйте вместе цифры `Infinity`
- `stablesForInteraction` отвечает за то, сколько будет тратиться стейблов в каком-то из действий (от и до)

## Перед запуском

Основной стейбл для BSC - **USDT**, для остальных сетей - **USDC**

1. Раскидываете по желаемым сетям комсу (от $2)
2. Кидаете в одну из сетей стейблов (от $1.25)
3. Вносите приватники в файл `keys.example.json` (нужны приватники для EVM и Aptos, внутри есть пример)
4. Переименовываете `keys.example.json` на `keys.json`
5. Запускаете софт

## Инструкция по запуску

1. Установите [Nodejs](https://nodejs.org/en/download)
2. Клонируйте репозиторий или скачайте архивом
3. Зайдите в папку с софтом в консоли и напишите команду `npm install`
4. Введите в консоль `npm run start` для запуска софта

Если вы найдете баги или столкнетесь с другими проблемами по поводу софта - пишите [@rubyuroboros](https://t.me/rubyuroboros) в Telegram или в паблик под постом.
