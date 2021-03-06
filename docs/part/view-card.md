﻿section: view
id: card
description: 可以展示图片和文本的卡片网格视图
icon: icon-th
filter: kapian kp
---

# 卡片

卡片视图用来在网格组织带图片和标题的卡片内容，以下为ZUI中卡片视图的结构：

<table class="table">
  <tbody>
    <tr>
      <td>头部</td>
      <td>包含当前列表标题</td>
    </tr>
    <tr>
      <td>列表</td>
      <td>多个列表部分请使用`section`</td>
    </tr>
    <tr>
      <td>底部</td>
      <td>底部显示页码及其他提示信息</td>
    </tr>
  </tbody>
</table>

## 包含图片链接的卡片

点击图片即可转向指定的链接地址。

<div contenteditable="false" spellcheck="false" class="example">
  <br>
  <ul class="breadcrumb breadcrumb-block">
    <li><i class="icon-location-arrow icon-muted"></i></li>
    <li><a href="#">Home</a></li>
    <li><a href="#">Library</a></li>
    <li class="active">Data</li>
  </ul>
  <div class="list">
    <header>
      <div class="pull-right">
        <div class="btn-group" data-toggle="buttons-radio">
          <button type="button" class="btn btn-default active"><i class="icon-th-list"></i></button>
          <button type="button" class="btn btn-default"><i class="icon-th"></i></button>
          <button type="button" class="btn btn-default"><i class="icon-th-large"></i></button>
        </div>
      </div>
      <h3><i class="icon-list-ul icon-border-circle"></i> Cards &nbsp;<small>26 items</small></h3>
    </header>
    <section class="cards">
      <div class="col-md-4 col-sm-6 col-lg-3">
        <a href="###" class="card">
          <img src="docs/img/img4.jpg" alt="">
          <span class="caption">关于图片的说明</span>
        </a>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <a href="###" class="card">
          <img src="docs/img/img5.jpg" alt="">
          <span class="caption">关于图片的超多多多多多多多多多多多多多多多多多多多多多多多多多说明</span>
        </a>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <a href="###" class="card"><img src="docs/img/img1.jpg" alt=""></a>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <a href="###" class="card"><img src="docs/img/img2.jpg" alt=""></a>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <a href="###" class="card"><img src="docs/img/img3.jpg" alt=""></a>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <a href="###" class="card"><img src="docs/img/img4.jpg" alt=""></a>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <a href="###" class="card"><img src="docs/img/img5.jpg" alt=""></a>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <a href="###" class="card"><img src="docs/img/img1.jpg" alt=""></a>
      </div>
    </section>
    <footer>
      <ul class="pager">
        <li class="previous"><a href="#">« 上一页</a></li>
        <li><a href="#">1</a></li>
        <li><a href="#">⋯</a></li>
        <li><a href="#">6</a></li>
        <li class="active"><a href="#">7</a></li>
        <li><a href="#">8</a></li>
        <li><a href="#">9</a></li>
        <li><a href="#">⋯</a></li>
        <li><a href="#">12</a></li>
        <li class="next"><a href="#">下一页 »</a></li>
      </ul>
    </footer>
  </div>
</div>

## 图片链接＋标题

点击卡片即可转向指定的链接地址。

<div contenteditable="false" spellcheck="false" class="example">
  <br>
  <ul class="breadcrumb breadcrumb-block">
    <li><i class="icon-location-arrow icon-muted"></i></li>
    <li><a href="#">Home</a></li>
    <li><a href="#">Library</a></li>
    <li class="active">Data</li>
  </ul>
  <div class="list">
    <header>
      <div class="pull-right">
        <div class="btn-group" data-toggle="buttons-radio">
          <button type="button" class="btn btn-default active"><i class="icon-th-list"></i></button>
          <button type="button" class="btn btn-default"><i class="icon-th"></i></button>
          <button type="button" class="btn btn-default"><i class="icon-th-large"></i></button>
        </div>
      </div>
      <h3><i class="icon-list-ul icon-border-circle"></i> Cards &nbsp;<small>26 items</small></h3>
    </header>
    <section class="cards">
      <div class="col-md-4 col-sm-6 col-lg-3">
        <a href="###" class="card">
          <img src="docs/img/img1.jpg" alt="">
          <span class="caption">关于图片的说明</span>
          <strong class="card-heading">图片标题</strong>
        </a>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <a href="###" class="card">
          <img src="docs/img/img2.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <h5 class="card-heading">Lorem ipsum dolor sit.</h5>
        </a>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <a href="###" class="card">
          <img src="docs/img/img3.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <h5 class="card-heading">Lorem ipsum dolor sit.</h5>
        </a>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <a href="###" class="card">
          <img src="docs/img/img4.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <h5 class="card-heading">Lorem ipsum dolor sit.</h5>
        </a>
      </div>
    </section>
    <section class="cards">
      <div class="col-md-4 col-sm-6 col-lg-3">
        <a href="###" class="card">
          <img src="docs/img/img5.jpg" alt="">
          <span class="caption">关于图片的说明</span>
          <h5 class="card-heading">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quaerat, autem dolorum accusantium laboriosam architecto veritatis eaque pariatur quisquam ea odit.</h5>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
        </a>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <a href="###" class="card">
          <img src="docs/img/img1.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <h5 class="card-heading">Lorem ipsum dolor sit.</h5>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
        </a>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <a href="###" class="card">
          <img src="docs/img/img2.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <h5 class="card-heading">Lorem ipsum dolor sit.</h5>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
        </a>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <a href="###" class="card">
          <img src="docs/img/img3.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <h5 class="card-heading">Lorem ipsum dolor sit.</h5>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
        </a>
      </div>
    </section>
    <footer>
      <ul class="pager">
        <li class="previous"><a href="#">« 上一页</a></li>
        <li><a href="#">1</a></li>
        <li><a href="#">⋯</a></li>
        <li><a href="#">6</a></li>
        <li class="active"><a href="#">7</a></li>
        <li><a href="#">8</a></li>
        <li><a href="#">9</a></li>
        <li><a href="#">⋯</a></li>
        <li><a href="#">12</a></li>
        <li class="next"><a href="#">下一页 »</a></li>
      </ul>
    </footer>
  </div>
</div>

## 图片＋标题链接

需要点击标题才可以打开链接地址。

<div contenteditable="false" spellcheck="false" class="example">
  <br>
  <ul class="breadcrumb breadcrumb-block">
    <li><i class="icon-location-arrow icon-muted"></i></li>
    <li><a href="#">Home</a></li>
    <li><a href="#">Library</a></li>
    <li class="active">Data</li>
  </ul>
  <div class="list">
    <header>
      <div class="pull-right">
        <div class="btn-group" data-toggle="buttons-radio">
          <button type="button" class="btn btn-default active"><i class="icon-th-list"></i></button>
          <button type="button" class="btn btn-default"><i class="icon-th"></i></button>
          <button type="button" class="btn btn-default"><i class="icon-th-large"></i></button>
        </div>
      </div>
      <h3><i class="icon-list-ul icon-border-circle"></i> Cards &nbsp;<small>26 items</small></h3>
    </header>
    <section class="cards">
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img1.jpg" alt="">
          <span class="caption">关于图片的说明</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img2.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img3.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <div class="card-heading">
            <span class="pull-right"><a href="###"><i class="icon-heart-empty"></i></a></span>
            <a href="###"><strong>Lorem ipsum dolor sit.</strong></a>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img4.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <div class="card-heading">
            <span class="pull-right"><a href="###"><i class="icon-heart-empty"></i> 123</a></span>
            <a href="###"><strong>Lorem ipsum dolor sit.</strong></a>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img5.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <div class="card-heading">
            <span class="pull-right"><a href="###"><i class="icon-star-empty"></i></a></span>
            <a href="###"><strong>Lorem ipsum dolor sit.</strong></a>
          </div>
          <div class="card-actions">
            <a href="###"><i class="icon-comment"></i> 343</a>
            <span class="text-muted">&nbsp;&nbsp;2013-11-12 15:05:56</span>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img1.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-actions">
            <a href="###"><i class="icon-comment"></i> 343</a>
            <span class="text-muted">&nbsp;&nbsp;2013-11-12 15:05:56</span>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img2.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-actions">
            <span class="label">tag1</span>
            <a href="###" class="pull-right"><i class="icon-comment"></i> 343</a>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img3.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-actions">
            <span class="label">tag1</span>
            <a href="###" class="pull-right"><i class="icon-comment"></i> 343</a>
          </div>
        </div>
      </div>
    </section>
    <section class="cards">
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img4.jpg" alt="">
          <span class="caption">关于图片的说明</span>
          <h5 class="card-heading">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quaerat, autem dolorum accusantium laboriosam architecto veritatis eaque pariatur quisquam ea odit.</h5>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
          <div class="card-actions">
            <a href="###"><i class="icon-comment"></i> 343</a>
            <span class="text-muted">&nbsp;&nbsp;2013-11-12 15:05:56</span>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img5.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
          <div class="card-actions">
            <a href="###"><i class="icon-comment"></i> 343</a>
            <span class="text-muted">&nbsp;&nbsp;2013-11-12 15:05:56</span>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img1.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
          <div class="card-actions">
            <span class="label">tag1</span>
            <a href="###" class="pull-right"><i class="icon-comment"></i> 343</a>
          </div>
        </div>
      </div><div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img2.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
          <div class="card-actions">
            <span class="label">tag1</span>
            <a href="###" class="pull-right"><i class="icon-comment"></i> 343</a>
          </div>
        </div>
      </div><div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img3.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
          <div class="card-actions">
            <button class="btn"><i class="icon-search"></i> 查看</button>
          </div>
        </div>
      </div><div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img4.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
          <div class="card-actions">
            <button class="btn btn-primary"><i class="icon-shopping-cart"></i> 订购</button>
          </div>
        </div>
      </div><div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img5.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
          <div class="card-actions">
            <button class="btn btn-success"><i class="icon-comments-alt"></i> 参与讨论</button>
          </div>
        </div>
      </div><div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img1.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
          <div class="card-actions">
            <button class="btn btn-danger"><i class="icon-smile"></i> 喜欢</button>
          </div>
        </div>
      </div>
    </section>
    <footer>
      <ul class="pager">
        <li class="previous"><a href="#">« 上一页</a></li>
        <li><a href="#">1</a></li>
        <li><a href="#">⋯</a></li>
        <li><a href="#">6</a></li>
        <li class="active"><a href="#">7</a></li>
        <li><a href="#">8</a></li>
        <li><a href="#">9</a></li>
        <li><a href="#">⋯</a></li>
        <li><a href="#">12</a></li>
        <li class="next"><a href="#">下一页 »</a></li>
      </ul>
    </footer>
  </div>
</div>

## 为图片增加 .media-wrapper 容器

为图片增加 `.media-wrapper` 容器，用来为图标固定尺寸和设置特殊效果。

<div contenteditable="false" spellcheck="false" class="example">
  <br>
  <ul class="breadcrumb breadcrumb-block">
    <li><i class="icon-location-arrow icon-muted"></i></li>
    <li><a href="#">Home</a></li>
    <li><a href="#">Library</a></li>
    <li class="active">Data</li>
  </ul>
  <div class="list">
    <header>
      <div class="pull-right">
        <div class="btn-group" data-toggle="buttons-radio">
          <button type="button" class="btn btn-default active"><i class="icon-th-list"></i></button>
          <button type="button" class="btn btn-default"><i class="icon-th"></i></button>
          <button type="button" class="btn btn-default"><i class="icon-th-large"></i></button>
        </div>
      </div>
      <h3><i class="icon-list-ul icon-border-circle"></i> Cards &nbsp;<small>26 items</small></h3>
    </header>
    <section class="cards">
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <a href="#" class="media-wrapper"><img src="docs/img/img1.jpg" alt=""></a>
          <span class="caption">.media-wrapper 也可以是一个链接</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <div class="media-wrapper"><img src="docs/img/img2.jpg" alt=""></div>
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <div class="media-wrapper"><img src="docs/img/img3.jpg" alt=""></div>
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <div class="card-heading">
            <span class="pull-right"><a href="###"><i class="icon-heart-empty"></i></a></span>
            <a href="###"><strong>Lorem ipsum dolor sit.</strong></a>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <div class="media-wrapper"><img src="docs/img/img4.jpg" alt=""></div>
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <div class="card-heading">
            <span class="pull-right"><a href="###"><i class="icon-heart-empty"></i> 123</a></span>
            <a href="###"><strong>Lorem ipsum dolor sit.</strong></a>
          </div>
        </div>
      </div>
    </section>
    <footer>
      <ul class="pager">
        <li class="previous"><a href="#">« 上一页</a></li>
        <li><a href="#">1</a></li>
        <li><a href="#">⋯</a></li>
        <li><a href="#">6</a></li>
        <li class="active"><a href="#">7</a></li>
        <li><a href="#">8</a></li>
        <li><a href="#">9</a></li>
        <li><a href="#">⋯</a></li>
        <li><a href="#">12</a></li>
        <li class="next"><a href="#">下一页 »</a></li>
      </ul>
    </footer>
  </div>
</div>

## 无边框卡片

为 `.cards` 增加 `.cards-borderless`。

<div contenteditable="false" spellcheck="false" class="example">
  <br>
  <ul class="breadcrumb breadcrumb-block">
    <li><i class="icon-location-arrow icon-muted"></i></li>
    <li><a href="#">Home</a></li>
    <li><a href="#">Library</a></li>
    <li class="active">Data</li>
  </ul>
  <div class="list">
    <header>
      <div class="pull-right">
        <div class="btn-group" data-toggle="buttons-radio">
          <button type="button" class="btn btn-default active"><i class="icon-th-list"></i></button>
          <button type="button" class="btn btn-default"><i class="icon-th"></i></button>
          <button type="button" class="btn btn-default"><i class="icon-th-large"></i></button>
        </div>
      </div>
      <h3><i class="icon-list-ul icon-border-circle"></i> Cards &nbsp;<small>26 items</small></h3>
    </header>
    <section class="cards cards-borderless">
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <div class="media-wrapper"><img src="docs/img/img5.jpg" alt=""></div>
          <span class="caption">关于图片的说明</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <div class="media-wrapper"><img src="docs/img/img1.jpg" alt=""></div>
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <div class="media-wrapper"><img src="docs/img/img2.jpg" alt=""></div>
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <div class="card-heading">
            <span class="pull-right"><a href="###"><i class="icon-heart-empty"></i></a></span>
            <a href="###"><strong>Lorem ipsum dolor sit.</strong></a>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <div class="media-wrapper"><img src="docs/img/img3.jpg" alt=""></div>
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <div class="card-heading">
            <span class="pull-right"><a href="###"><i class="icon-heart-empty"></i> 123</a></span>
            <a href="###"><strong>Lorem ipsum dolor sit.</strong></a>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <div class="media-wrapper"><img src="docs/img/img4.jpg" alt=""></div>
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <div class="card-heading">
            <span class="pull-right"><a href="###"><i class="icon-star-empty"></i></a></span>
            <a href="###"><strong>Lorem ipsum dolor sit.</strong></a>
          </div>
          <div class="card-actions">
            <a href="###"><i class="icon-comment"></i> 343</a>
            <span class="text-muted">&nbsp;&nbsp;2013-11-12 15:05:56</span>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <div class="media-wrapper"><img src="docs/img/img5.jpg" alt=""></div>
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-actions">
            <a href="###"><i class="icon-comment"></i> 343</a>
            <span class="text-muted">&nbsp;&nbsp;2013-11-12 15:05:56</span>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <div class="media-wrapper"><img src="docs/img/img1.jpg" alt=""></div>
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-actions">
            <span class="label">tag1</span>
            <a href="###" class="pull-right"><i class="icon-comment"></i> 343</a>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <div class="media-wrapper"><img src="docs/img/img2.jpg" alt=""></div>
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-actions">
            <span class="label">tag1</span>
            <a href="###" class="pull-right"><i class="icon-comment"></i> 343</a>
          </div>
        </div>
      </div>
    </section>
    <section class="cards cards-borderless">
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img3.jpg" alt="">
          <span class="caption">关于图片的说明</span>
          <h5 class="card-heading">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quaerat, autem dolorum accusantium laboriosam architecto veritatis eaque pariatur quisquam ea odit.</h5>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
          <div class="card-actions">
            <a href="###"><i class="icon-comment"></i> 343</a>
            <span class="text-muted">&nbsp;&nbsp;2013-11-12 15:05:56</span>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img4.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
          <div class="card-actions">
            <a href="###"><i class="icon-comment"></i> 343</a>
            <span class="text-muted">&nbsp;&nbsp;2013-11-12 15:05:56</span>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img5.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
          <div class="card-actions">
            <span class="label">tag1</span>
            <a href="###" class="pull-right"><i class="icon-comment"></i> 343</a>
          </div>
        </div>
      </div><div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img1.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
          <div class="card-actions">
            <span class="label">tag1</span>
            <a href="###" class="pull-right"><i class="icon-comment"></i> 343</a>
          </div>
        </div>
      </div><div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img2.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
          <div class="card-actions">
            <button class="btn"><i class="icon-search"></i> 查看</button>
          </div>
        </div>
      </div><div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img3.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
          <div class="card-actions">
            <button class="btn btn-primary"><i class="icon-shopping-cart"></i> 订购</button>
          </div>
        </div>
      </div><div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img4.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
          <div class="card-actions">
            <button class="btn btn-success"><i class="icon-comments-alt"></i> 参与讨论</button>
          </div>
        </div>
      </div><div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img5.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
          <div class="card-actions">
            <button class="btn btn-danger"><i class="icon-smile"></i> 喜欢</button>
          </div>
        </div>
      </div>
    </section>
    <footer>
      <ul class="pager">
        <li class="previous"><a href="#">« 上一页</a></li>
        <li><a href="#">1</a></li>
        <li><a href="#">⋯</a></li>
        <li><a href="#">6</a></li>
        <li class="active"><a href="#">7</a></li>
        <li><a href="#">8</a></li>
        <li><a href="#">9</a></li>
        <li><a href="#">⋯</a></li>
        <li><a href="#">12</a></li>
        <li class="next"><a href="#">下一页 »</a></li>
      </ul>
    </footer>
  </div>
</div>

## 更为紧凑的模式

`.cards-condensed`

<div contenteditable="false" spellcheck="false" class="example">
  <br>
  <ul class="breadcrumb breadcrumb-block">
    <li><i class="icon-location-arrow icon-muted"></i></li>
    <li><a href="#">Home</a></li>
    <li><a href="#">Library</a></li>
    <li class="active">Data</li>
  </ul>
  <div class="list">
    <header>
      <div class="pull-right">
        <div class="btn-group" data-toggle="buttons-radio">
          <button type="button" class="btn btn-default active"><i class="icon-th-list"></i></button>
          <button type="button" class="btn btn-default"><i class="icon-th"></i></button>
          <button type="button" class="btn btn-default"><i class="icon-th-large"></i></button>
        </div>
      </div>
      <h3><i class="icon-list-ul icon-border-circle"></i> Cards &nbsp;<small>26 items</small></h3>
    </header>
    <section class="cards cards-condensed">
      <div class="col-md-4 col-sm-6 col-lg-3">
        <a href="###" class="card">
          <img src="docs/img/img1.jpg" alt="">
          <span class="caption">关于图片的说明</span>
        </a>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <a href="###" class="card">
          <img src="docs/img/img2.jpg" alt="">
          <span class="caption">关于图片的超多多多多多多多多多多多多多多多多多多多多多多多多多说明</span>
        </a>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <a href="###" class="card"><img src="docs/img/img3.jpg" alt=""></a>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <a href="###" class="card"><img src="docs/img/img4.jpg" alt=""></a>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img5.jpg" alt="">
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-reveal">
            <h5 class="card-heading">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quaerat, autem dolorum accusantium laboriosam architecto veritatis eaque pariatur quisquam ea odit.</h5>
            <div class="card-actions">
                <a href="###"><i class="icon-comment"></i> 343</a>
                <span class="text-muted">&nbsp;&nbsp;2013-11-12 15:05:56</span>
            </div>
            <div class="card-content text-muted">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
            </div>
            <div class="card-actions">
              <button class="btn btn-success"><i class="icon-comments-alt"></i> 参与讨论</button>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img1.jpg" alt="">
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-reveal">
            <h5 class="card-heading">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quaerat, autem dolorum accusantium laboriosam architecto veritatis eaque pariatur quisquam ea odit.</h5>
            <div class="card-actions">
                <a href="###"><i class="icon-comment"></i> 343</a>
                <span class="text-muted">&nbsp;&nbsp;2013-11-12 15:05:56</span>
            </div>
            <div class="card-content text-muted">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
            </div>
            <div class="card-actions">
              <button class="btn btn-success"><i class="icon-comments-alt"></i> 参与讨论</button>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img2.jpg" alt="">
          <div class="card-heading">
            <span class="pull-right"><a href="###"><i class="icon-heart-empty"></i></a></span>
            <a href="###"><strong>Lorem ipsum dolor sit.</strong></a>
          </div>
          <div class="card-reveal">
            <h5 class="card-heading">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quaerat, autem dolorum accusantium laboriosam architecto veritatis eaque pariatur quisquam ea odit.</h5>
            <div class="card-actions">
                <a href="###"><i class="icon-comment"></i> 343</a>
                <span class="text-muted">&nbsp;&nbsp;2013-11-12 15:05:56</span>
            </div>
            <div class="card-content text-muted">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
            </div>
            <div class="card-actions">
              <button class="btn btn-success"><i class="icon-comments-alt"></i> 参与讨论</button>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img3.jpg" alt="">
          <div class="card-heading">
            <span class="pull-right"><a href="###"><i class="icon-heart-empty"></i> 123</a></span>
            <a href="###"><strong>Lorem ipsum dolor sit.</strong></a>
          </div>
          <div class="card-reveal">
            <h5 class="card-heading">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quaerat, autem dolorum accusantium laboriosam architecto veritatis eaque pariatur quisquam ea odit.</h5>
            <div class="card-actions">
                <a href="###"><i class="icon-comment"></i> 343</a>
                <span class="text-muted">&nbsp;&nbsp;2013-11-12 15:05:56</span>
            </div>
            <div class="card-content text-muted">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
            </div>
            <div class="card-actions">
              <button class="btn btn-success"><i class="icon-comments-alt"></i> 参与讨论</button>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img4.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <div class="card-heading">
            <span class="pull-right"><a href="###"><i class="icon-star-empty"></i></a></span>
            <a href="###"><strong>Lorem ipsum dolor sit.</strong></a>
          </div>
          <div class="card-actions">
            <a href="###"><i class="icon-comment"></i> 343</a>
            <span class="text-muted">&nbsp;&nbsp;2013-11-12 15:05:56</span>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img5.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-actions">
            <a href="###"><i class="icon-comment"></i> 343</a>
            <span class="text-muted">&nbsp;&nbsp;2013-11-12 15:05:56</span>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img1.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-actions">
            <span class="label">tag1</span>
            <a href="###" class="pull-right"><i class="icon-comment"></i> 343</a>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img2.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-actions">
            <span class="label">tag1</span>
            <a href="###" class="pull-right"><i class="icon-comment"></i> 343</a>
          </div>
        </div>
      </div>
    </section>
    <section class="cards cards-condensed">
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img3.jpg" alt="">
          <span class="caption">关于图片的说明</span>
          <h5 class="card-heading">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quaerat, autem dolorum accusantium laboriosam architecto veritatis eaque pariatur quisquam ea odit.</h5>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
          <div class="card-actions">
            <a href="###"><i class="icon-comment"></i> 343</a>
            <span class="text-muted">&nbsp;&nbsp;2013-11-12 15:05:56</span>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img4.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
          <div class="card-actions">
            <a href="###"><i class="icon-comment"></i> 343</a>
            <span class="text-muted">&nbsp;&nbsp;2013-11-12 15:05:56</span>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img5.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
          <div class="card-actions">
            <span class="label">tag1</span>
            <a href="###" class="pull-right"><i class="icon-comment"></i> 343</a>
          </div>
        </div>
      </div><div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img1.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
          <div class="card-actions">
            <span class="label">tag1</span>
            <a href="###" class="pull-right"><i class="icon-comment"></i> 343</a>
          </div>
        </div>
      </div><div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img2.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
          <div class="card-actions">
            <button class="btn"><i class="icon-search"></i> 查看</button>
          </div>
        </div>
      </div><div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img3.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
          <div class="card-actions">
            <button class="btn btn-primary"><i class="icon-shopping-cart"></i> 订购</button>
          </div>
        </div>
      </div><div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img4.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
          <div class="card-actions">
            <button class="btn btn-success"><i class="icon-comments-alt"></i> 参与讨论</button>
          </div>
        </div>
      </div><div class="col-md-4 col-sm-6 col-lg-3">
        <div class="card">
          <img src="docs/img/img5.jpg" alt="">
          <span class="caption">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste, voluptatem.</span>
          <a href="###" class="card-heading"><strong>Lorem ipsum dolor sit.</strong></a>
          <div class="card-content text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae, officia similique enim culpa ipsam voluptas. Quibusdam, tempora autem voluptatem aliquid!
          </div>
          <div class="card-actions">
            <button class="btn btn-danger"><i class="icon-smile"></i> 喜欢</button>
          </div>
        </div>
      </div>
    </section>
    <footer>
      <ul class="pager">
        <li class="previous"><a href="#">« 上一页</a></li>
        <li><a href="#">1</a></li>
        <li><a href="#">⋯</a></li>
        <li><a href="#">6</a></li>
        <li class="active"><a href="#">7</a></li>
        <li><a href="#">8</a></li>
        <li><a href="#">9</a></li>
        <li><a href="#">⋯</a></li>
        <li><a href="#">12</a></li>
        <li class="next"><a href="#">下一页 »</a></li>
      </ul>
    </footer>
  </div>
</div>

<div class="alert with-icon">
  <i class="icon-smile"></i>
  <div class="content">
    <p>非常感谢 <a class="alert-link" href="http://weibo.com/snowinfish" target="_blank">@snowinfish</a> 为本章节提供演示所用的全部图片。</p>
    <p class="margin-zero">图片仅供 ZUI 演示使用，未经作者授权，不得用作他用。</p>
  </div>
</div>
