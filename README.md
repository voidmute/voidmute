

<div align="center">

<img src="https://raw.githubusercontent.com/voidmute/Spotti/main/admin/public/favicon.svg" width="72" height="72" alt="voidmute" />

### привет, я **voidmute**

собираю ботов, голосовой ИИ, веб-админки и утилиты под Windows.  
больше всего времени уходит на **Discord-сообщества** и всё, что вокруг них крутится.

[![Spotti](https://img.shields.io/badge/флагман-Spotti-5865F2)](https://github.com/voidmute/Spotti)
[![site](https://img.shields.io/badge/site-spottibot.duckdns.org-111111)](https://spottibot.duckdns.org)

</div>

## Чем занимаюсь

- **Discord-боты** - модерация, тикеты, голосовые комнаты, дашборды
- **Голосовой ИИ** - STT, LLM, TTS, память, низкая задержка в войсе
- **Веб-админки** - OAuth, выдача доступа, веб-чат, статус сервисов
- **Инфра** - VPS, nginx, деплой-скрипты, миграции БД
- **Windows-утилиты** - сканеры и десктопные инструменты (в т.ч. для GTA5RP / RAGE.MP)

## Главный проект

| | |
| --- | --- |
| **[Spotti](https://github.com/voidmute/Spotti)** | Discord-бот с голосовым ИИ и админкой. Монорепо: бот, админ-сайт [spottibot.duckdns.org](https://spottibot.duckdns.org), checker для PC-check, Alembic, тесты. |
| Стек | Python, Discord.py, голосовой пайплайн (Deepgram / OpenAI, Claude, ElevenLabs), веб-админка, Postgres |

```bash
git clone https://github.com/voidmute/Spotti.git
cd Spotti
cp .env.example .env   # ключи только локально
python deploy.py install && python deploy.py run
```

## Ещё в работе (локально)

Публично пока не на GitHub - но это тот же «почерк»:

| Проект | Суть |
| --- | --- |
| **JARVIS** | Монорепо: голосовой ассистент (backend + frontend, Bun) |
| **Multiplayer Paint** | Совместный рисунок в браузере в реальном времени |
| **Hands Recognition** | Распознавание жестов / рук |
| **Spotti Checker** | Уже внутри [Spotti](https://github.com/voidmute/Spotti/tree/main/checker) - античит-скан под Windows |

## Стек (коротко)

`Python` · `TypeScript` · `Discord` · `Postgres` · `Alembic` · `nginx` · `VPS` · `Windows` · `LLM` · `STT/TTS`

## Связь

- Сайт проекта: [spottibot.duckdns.org](https://spottibot.duckdns.org)
- Репозиторий: [github.com/voidmute/Spotti](https://github.com/voidmute/Spotti)

---

<sub>MIT там, где написано MIT. Белая точка в favicon - фирменный знак, не баг.</sub>
