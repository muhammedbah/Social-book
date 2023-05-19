.story-gallery {
    display: flex;
    justify-content: space-between;
    margin-bottom: 20px;
}

.story {
    flex-basis: 18%;
    padding-top: 32%;
    position: relative;
    
    background-position: center;
    background-size: cover;
    border-radius: 10px;

}

.story img {
    position: absolute;
    width: 45px;
    border-radius: 50px;
    top: 10px;
    left: 10px;
    border: 5px solid #1876f2;
}

.story p {
    position: absolute;
    bottom: 10px;
    width: 100%;
    text-align: center;
    color: #fff;
    font-size: 14px;
}

.story1 {
    background-image: linear-gradient(transparent, rgba(0,0,0,0.5)), url("../images/status-1.png");
}

.story2 {
    background-image: linear-gradient(transparent, rgba(0,0,0,0.5)), url("../images/status-2.png");
}

.story3 {
    background-image: linear-gradient(transparent, rgba(0,0,0,0.5)), url("../images/status-3.png");
}

.story4 {
    background-image: linear-gradient(transparent, rgba(0,0,0,0.5)), url("../images/status-4.png");
}

.story5 {
    background-image: linear-gradient(transparent, rgba(0,0,0,0.5)), url("../images/status-5.png");
}

.story.story1 img {
    top: unset;
    left: 50%;
    bottom: 40px;
    transform: translateX(-50%);
    border: 0;
    width: 35px;
}

.write-post-container {
    width: 100%;
    background: #fff;
    border-radius: 6px;
    padding: 15px;
    color: #626262;
    
}

.user-profile {
    display: flex;
    align-items: center;
}

.user-profile img {
    width: 45px;
    border-radius: 50%;
    margin-right: 10px;
}

.user-profile p {
    margin-bottom: -5px;
    font-weight: 500;
    color: #626262;
}

.user-profile small {
   font-size: 12px; 
}

.post-input-container {
    padding-left: 55px;
    padding-top: 20px;

}

.post-input-container textarea {
    width: 100%;
    border: 0;
    outline: 0;
    border-bottom: 1px solid #ccc;
    background: transparent;
    resize: none;
}

.add-post-links {
    display: flex;
    margin-top: 10px;
}

.add-post-links a {
    text-decoration: none;
    display: flex;
    align-items: center;
    color: #626262;
    margin-right: 30px;
    font-size: 13px;
}

.add-post-links img {
    width: 20px;
    margin-right: 10px;
}

.post-container {
    width: 100%;
    background: #fff;
    border-radius: 6px;
    color: #626262;
    margin: 20px 0; 
}