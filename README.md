# The ThinkPHP5 Image Package

## 安装

> composer require topthink/think-image

## 使用

~~~
$image = \think\image\Image::open('./image.jpg');
或者
$image = \think\image\Image::open(request()->file('image'));


$image->crop(...)
    ->thumb(...)
    ->water(...)
    ->text(....)
    ->save(..);

~~~