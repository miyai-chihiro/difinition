# difinition  〜 よくみかける変数名の定義 〜

## dist

district?? distinguish?? 区別する的な？？ 本番とdev と区別する意味？  

    dev: {
      files: 'main.css',['main.scss']
    },
    dist: {
      files: 'main.min.css' : ['main.scss']
    }

## dest  

> “destinationの略。移動先。src (source) の対義語。プログラミング用語。  
<http://kndys.tumblr.com/post/346851988/destination-src-source>  

    min: {
        dist: {
            src: ['main.css'],
            dest: 'main.min.css'
        }
    }
