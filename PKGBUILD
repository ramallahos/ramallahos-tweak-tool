# Maintainer: Safwan Nayeem Yousuf <safwannayeemyousuf.com>
pkgname=ramallahos-tweak-tool
pkgver=1
pkgrel=1
pkgdesc="Tweak tool for RamallahOS"
arch=('any')
url="https://github.com/ramallahos/$pkgname"
license=('GPL3')
depends=('yad')
makedepends=('coreutils')
source=("$pkgname::git+$url.git")
sha256sums=('SKIP')

package() {
    cd "$pkgname"
    install -d "${pkgdir}/usr/share/resources/${pkgname}/"
    install -Dm 755 "add" "${pkgdir}/usr/share/resources/${pkgname}/add"
    install -Dm 755 "functions" "${pkgdir}/usr/share/resources/${pkgname}/functions"
    install -Dm 755 "home.html" "${pkgdir}/usr/share/resources/${pkgname}/home.html"
    install -Dm 755 "main" "${pkgdir}/usr/share/resources/${pkgname}/main"
    install -Dm 755 "main.html" "${pkgdir}/usr/share/resources/${pkgname}/main.html"
    install -Dm 755 "ramallahos-tweak-tool" "${pkgdir}/usr/bin/${pkgname}"
    install -Dm 755 "users" "${pkgdir}/usr/share/resources/${pkgname}/users"
    install -Dm 755 "users.html" "${pkgdir}/usr/share/resources/${pkgname}/users.html"
}
