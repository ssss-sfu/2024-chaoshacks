# 2024-chaoshacks
Website for SystemsHacks 2024 - ChaosHacks

## Compiling SCSS
To compile all the scss files in src folder into compressed single main.css file in build folder, do this:

`sass --no-source-map --style=compressed --watch src/styles/main.scss:build/main.css`

Note: make sure this command is run on the root folder directory - 2024-chaoshacks