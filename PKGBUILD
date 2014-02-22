# Contributor: Wes Brown <wesbrown18@gmail.com>
pkgname=python2-olefileio
pkgver=0.30
pkgrel=0
pkgdesc="This is a Python library to parse OLE files."
arch=('i686' 'x86_64')
url=("http://www.decalage.info/python/olefileio")
license=('MIT')
depends=('python2')
source=("https://bitbucket.org/decalage/olefileio_pl/downloads/OleFileIO_PL-${pkgver}.zip")
md5sums=('6867f4940019979fe8c2738596fbf262')

build() {
  cd "$srcdir/OleFileIO_PL-${pkgver}"
  python2 setup.py build install --root="${pkgdir}" || return 1
}

# vim:set ts=2 sw=2 et:
