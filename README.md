```math
\ce{$\unicode[goombafont; color: red; 
pointer-events: none; 
position: fixed; 
top: calc(40vh - (var(--mouse-y) / 10)); 
left: calc(20vw - (var(--mouse-x) / 10)); 
object-fit: cover; 
background-size: cover!important; 
width: 10vw; 
height: 10vw; 
animation: Toast--spinner infinite linear 30s, Overlay--motion-slideInRight infinite alternate 1.5s, Overlay--motion-slideDown infinite alternate 5s, Overlay--pulse infinite 3s; 
background: url('https://github.com/ascpixi/ascpixi/assets/44982772/e7351fe0-7b52-4521-b371-521000c07f5c'); 
transition: top 0.4s, left 0.4s, transform 0.5s;

/* Additional animations */
@keyframes Toast--spinner {
    0% { transform: rotate(0deg); }
    100% { transform: rotate(360deg); }
}

@keyframes Overlay--motion-slideInRight {
    0% { left: calc(20vw - (var(--mouse-x) / 10)); }
    100% { left: calc(60vw - (var(--mouse-x) / 10)); }
}

@keyframes Overlay--motion-slideDown {
    0% { top: calc(40vh - (var(--mouse-y) / 10)); }
    100% { top: calc(60vh - (var(--mouse-y) / 10)); }
}

@keyframes Overlay--pulse {
    0%, 100% { transform: scale(1); }
    50% { transform: scale(1.1); }
}]{x0000}$}
```
