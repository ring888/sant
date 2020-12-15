<template>
	<view class="search_cont">
		<view class="search">
			<image src="../../static/tab/home-s.png" mode="widthFix" class="search_img"></image>
			<input type="text" placeholder="请输入内容" disabled />
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
.search_cont {
	display:flex;
	justify-content: space-between;
	height: 70upx;
	align-items: center;
}

.search{
	height: 70upx;
	line-height: 70upx;
	width: 100%;
	display: flex;
	background-color: #C0C0C0;
	border-radius: 10rpx;
}

.search_img{
	margin: auto 0 auto 20upx;
	width: 40upx;
	height: 40upx;
}
.search input{
	height: 70upx;
	line-height: 70upx;
	width: 100%;
	font-size: 25upx;
	color: #666666;
}
</style>
