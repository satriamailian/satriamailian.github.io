# Satria landing pages

Satria adalah situs toko online dengan berbagai fitur yang memudahkan kamu buat mengelola dan mengembangkan bisnis kamu biar makin sukses.

## Contributing
Ada yang hilang atau salah? jangan ragu untuk create a pull request! Bagian berikut akan menjelaskan bagaimana Anda dapat berkontribusi ke situs dokumentasi kami.

## Development guide

### Prerequisites
Node.js (8.0.0+)

### Initial setup
Clone this repository.

```sh
git clone https://github.com/satriamailian/satriamailian.github.io
```

```sh
# npm
npm install
```

### Running the server
To start working on this documentation, you need to start a development server.

```sh
# npm
npm run dev
```

## Commit message guidelines

Kami menggunakan Commitizen dengan standar cz-conventional-changelog. Kami menyertakan Commitizen CLI di dalam repositori sehingga Anda dapat membuat pesan terformat hanya dengan mengetikkan npm commit.

### Format

```sh
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>

```

Baris pertama harus berisi tipe komit, cakupan opsional, dan subjek komit. Badan pesan berisi deskripsi perubahan yang lebih panjang. Ini dicadangkan untuk informasi apa pun yang tidak muat di dalam baris subjek pesan komit. Perhatikan bahwa setiap baris pesan komit tidak boleh lebih dari 72 karakter. Footer adalah opsional, dan berisi informasi tambahan apa pun untuk komit (mis. Masalah diperbaiki, melanggar perubahan).

### Commit types

Kami menggunakan tipe commit konvensional-changelog berikut:

```sh
feat:     A new feature
fix:      A bug fix
docs:     Documentation only changes
style:    Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
refactor: A code change that neither fixes a bug nor adds a feature
perf:     A code change that improves performance
test:     Adding missing tests or correcting existing tests
build:    Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
ci:       Changes to our CI configuration files and scripts (example scopes: travis, circle)
chore:    Other changes that don't modify src or test files
revert:   Reverts a previous commit
```

## Authors

[Satria Mailian Gumelar](https://github.com/satriamailian)

