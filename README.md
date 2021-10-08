
# admin=https://nikolav.rs/

# example usage:
fetch({
    url    :"./path/to/curlrequest.php",
    method : "post",
    data   : {
        url     : "www.page-to-fetch.com",
        // data : {}
    }
})
.then((response)=>{/* ...stuff */});
