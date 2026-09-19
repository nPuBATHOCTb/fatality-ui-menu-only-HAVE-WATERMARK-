
**Шаг 5. Добавь русский README.** Создай файл `README.ru.md`:

```markdown
# FatalityUI

 [🇷🇺 Русская версия](README.ru.md)

UI-библиотека в стиле Fatality для Roblox. **Только интерфейс** — никаких читов, эксплойтов и игровой логики. Просто красивое меню.

## Превью

![Превью](preview.png)

## Возможности

- Строгий дизайн в стиле Fatality (тёмная тема + красный акцент)
- Без скруглений — минималистичный вид
- Горизонтальные табы сверху с иконками
- Анимированные квадратные чекбоксы с галочкой
- Слайдеры с поддержкой перетаскивания
- Дропдауны (выпадающие списки)
- Секции с заголовками для группировки настроек
- Плавная прокрутка в колонках
- Блюр-эффект за меню
- Вотермарка с FPS и временем
- Палитра акцентных цветов (8 цветов)
- Панель конфигов с кнопками Save/Load/Reset/Delete
- Открытие меню через `Right Shift`

## Горячие клавиши

| Клавиша | Действие |
|---------|----------|
| `Right Shift` | Открыть / закрыть меню |

## Установка

1. Открой Roblox Studio
2. Вставь `LocalScript` внутрь `StarterGui`
3. Вставь содержимое файла `FatalityUI.lua`
4. Нажми **Play** (F5)

## Использование

```lua
-- Чекбокс
createCheckbox(tab.left, "Мой чекбокс", false)

-- Слайдер
createSlider(tab.left, "Мой слайдер", 50, 0, 100)

-- Дропдаун
createDropdown(tab.left, "Мой дропдаун", {"Опция 1", "Опция 2"}, 1)


# FatalityUI

[🇬🇧 English version](README.md)

Fatality-style UI library for Roblox. **Interface only** — no cheat features, no exploits, no game logic. Just a nice-looking menu.

## Preview

![Preview](preview.png)

## Features

- Fatality-style strict design (dark theme + red accent)
- No rounded corners — sharp minimal look
- Horizontal tabs at the top with icons
- Animated toggle switches (square checkboxes with checkmark)
- Sliders with drag support
- Dropdown menus
- Section headers for grouping settings
- Smooth scrolling in columns
- Blur effect behind the menu
- Watermark with FPS and time
- Accent color palette (8 colors)
- Config panel with Save/Load/Reset/Delete buttons
- Menu toggle via `Right Shift`

## Hotkeys

| Key | Action |
|-----|--------|
| `Right Shift` | Open / close menu |

## Installation

1. Open Roblox Studio
2. Insert a `LocalScript` inside `StarterGui`
3. Paste the contents of `FatalityUI.lua`
4. Press **Play** (F5)

## Usage

```lua
-- Checkbox
createCheckbox(tab.left, "My Checkbox", false)

-- Slider
createSlider(tab.left, "My Slider", 50, 0, 100)

-- Dropdown
createDropdown(tab.left, "My Dropdown", {"Option 1", "Option 2"}, 1)

-- Section header
createSection(tab.left, "SECTION NAME")
-- Секция
createSection(tab.left, "НАЗВАНИЕ СЕКЦИИ")
