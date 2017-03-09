# qrcodejs
支持中文、自定义logo

使用：
var option = {
    render: "table",
    width: 230,//宽度
    height: 230,
    text: "除被扫支付场景以外，商户系统先调用该接口在微信支付服务后台生成预支付交易单，返回正确的预支付交易回话标识后再按扫码、JSAPI、APP等不同场景生成交易串调起支付。 ",
    background: "#ffffff", //二维码的后景色
    foreground: "#000000", //二维码的前景色
    src: '/static/img/weixin_pay_logo.jpg',
    imgWidth: 44,
    imgHeight: 44
};
$("#qrdiv").qrcode(option);

参考资料：
https://github.com/finfinity/jquery.qrcode

http://www.jb51.net/article/101893.htm
