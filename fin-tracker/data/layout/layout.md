# Standard Layout for ngx-ui-repo screens

## Breakpoint Min width Source

| Type   | width                                  | HPadding | Px   | Tpadding |
| ------ | -------------------------------------- | -------- | ---- | -------- |
| (base) | 0px Tailwind default                   |          |      |          |
| sm     | 640px Tailwind default                 | px-2     | 8px  | pt-2     |
| md     | 768px Tailwind default                 | px-2     | 8px  | pt-2     |
| lg     | 1024px Tailwind default                | px-4     | 16px | pt-4     |
| xl     | 1280px Tailwind default                | px-16    | 64px | pt-6     |
| 2xl    | 1536px Tailwind default                | px-16    | 64px | pt-6     |
| 3xl    | 1920px Full HD desktop                 | px-16    | 64px | pt-6     |
| 4xl    | 2560px QHD/2K desktop                  | px-16    | 64px | pt-6     |
| 5xl    | 3840px custom, (4K/very-large screens) | px-16    | 64px | pt-6     |

## Padding

## Right Panel

| rightWidth | input Below md | md and up                           |
| ---------- | -------------- | ----------------------------------- |
| w-12       | w-full         | md:w-12 (fixed, all the way to 5xl) |
| w-64       | w-full         | md:w-64 (fixed)                     |
| w-72       | w-full         | md:w-72 (fixed)                     |
| w-80       | w-full         | md:w-80 (fixed)                     |
| w-96       | w-full         | md:w-72 then xl:w-96                |

## grid layout

| Type   | width                   | Table | Chart | Grid Columns | Right panel |
| ------ | ----------------------- | ----- | ----- | ------------ | ----------- |
| 0-lg   | 1536px Tailwind default |       |       | 1            |             |
| lg-2xl | 1536px Tailwind default |       |       | 1            | 56          |
| 2xl    | 1536px Tailwind default |       |       | 2            | 64          |
| 2xl    | 1536px Tailwind default | 5     | 4     | 1            | 64          |
| 3xl    | 1920px Tailwind default |       |       | 2            | 72          |
| 3xl    | 1920px Tailwind default | 6     | 5     | 1            | 72          |
| 4xl    | 2560px Tailwind default | 6     | 5     | 2            | 80          |
