# JSwiper

欢迎直接使用simple版本

使用方法:

    example:

    <code>
        new JSwiper('className')
        
        new JSwiper('.swiper1',{
            afterSlide:function (index) {
                console.log(index)
            },
            autoplay:3000
        });

        new JSwiper('.swiper2',{
            direction:'vertical',
            autoplay:true
        });

    </code>    
    

目前支持配置：

    1.autoplay {number/boolean}

    2.direction {horizontal/vertical}

    3.afterSlide {callback function}
    

* 忽略history版本（太复杂，不好用）*


