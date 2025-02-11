# shvShells
bash aliases functions powershells

function shvhi(){
    echo "--made-history--> $@" ;
    history -s $@ ;
}
