# ntfy-shell
Notifycation about end of process by notify-send

Уведомление о завершении процесса с помощью notify-send

## Installation (Установка)

```
wget -O ~/.local/bin/n https://github.com/nixscript/ntfy-shell/raw/master/n
chmod +x ~/.local/bin/n
```

## Usage (Использование)

```
n -h
n --help

# Example
n gzip -9 archive.tar
```

## Options

```
	-c	critical notify-send
		# Уведомление висит пока не закроешь
	-n	normal notify-send (default)
		# Уведомление закрывается через 30 сек.
	-i path/to/icon	picture (png,jpg,svg)
		# В этот раз использовать иконку по указанному пути
	-e	end of options for '$O' (not required)
		# Ставится в конце опций для 'n'. Не требуется. Без неё работает.
	-h --help	this screen
		# Справка по использованию

	You can change icon by editing ICON value in 'n'.
	Можно поменять иконку указав путь в значении для ICON
```
