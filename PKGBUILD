# Contributor: Thomas S Hatch <thatch45@gmail.com>

pkgname=varch
pkgver=0.7.9
pkgrel=1
pkgdesc="ArchLinux virtual machine builder"
arch=(any)
url="http://code.google.com/p/varch/"
license=("GPL3")
depends=('python'
         'multipath-tools'
         'aif')
makedepends=('python')
optdepends=('virtualbox-ose: To enable support for virtualbox vdi images')
options=(!emptydirs)
source=("http://varch.googlecode.com/files/$pkgname-$pkgver.tar.gz")
md5sums=('d865611f2068ae4619af8269cf73ec70')

build() {
  cd $srcdir/$pkgname-$pkgver
    python setup.py install --root=$pkgdir/ --optimize=1
        }
        
