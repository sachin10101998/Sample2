---
layout: exercise
title: Exercise 3.12
permalink: /search-exercises/ex_12/
breadcrumb: 3-Solving-Problems-By-Searching
breadcrumb2: ex_12
breadcrumb3: 3solvingProblemsBySearching
---

{% include mathjax_support %}

<div class="card">
<div class="card-header p-2">
<a href='#' class="p-2">Exercise 12</a>
<button type="button" class="btn btn-dark float-right" title="Solve this Exercise" onclick="solve('ex3.12');" href="#"><i id="ex3.12" class="fas fa-pen" style="color:white"></i></button>
<a class="edit_question" href="#"><button type="button" class="btn btn-dark float-right" title="Edit this Question"  style="margin-left:10px; margin-right:10px;" onclick="edit('ex3.12');" href="#"><i id="ex3.12" class="far fa-edit" style="color:white"></i></button></a>
</div>
<div class="card-body">
<p class="card-text">{% include_relative question.md %}</p>
</div>
</div>
<br>
<div class="card">
    <div class="card-header p-2">
        <a href="#" class="p-2">Answers</a>


        <button type="button" class="btn btn-dark float-right" title="View Answers" id="viewanswers" onclick="myFunction()">
        <i id="view_answers1" class="fas fa-bars" style="color:white"></i>
        </button>

</div>
<div class="card">
    <div class="card-header p-2">
        <a href="#" class="p-2">Community Solution</a>



                <a class="reqcomm" id="reqcomm" href="#">
                <button type="button" class="btn btn-dark float-right" title="Request for Community Solution" href="#" id="requestcommsol">
                <i class="fas fa-hands" style="color:white"></i>
                </button>
                </a>

                <a class="viewcommsolution" id="viewcommsolution" href="#">
                <button type="button" class="btn btn-dark float-right" title="View Community solution" style="margin-left:10px; margin-right:10px;" onclick="myFunction2()" href="#" id="viewsol">
                <i class="fas fa-bars" style="color:white"></i>
                </button>
                </a>




          </div>
          <div class="card-body" id="hideandviewcommunitysolution">
          <p class="card-text">
          {% include_relative answers/communityanswer.md %}
          </p>
          </div>
          </div>
<br>
